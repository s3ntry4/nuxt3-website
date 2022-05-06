<script setup>
var times = useState('times', () => 0);
</script>

<template>
  <div>
    <button @click="times++" class="shadow border rounded">
      this button has been clicked {{ times }}
      <span v-if="times == 1">time</span>
      <span v-else>times</span>
    </button>
  </div>
</template>
