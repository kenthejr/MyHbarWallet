<template>
  <div class="test-print">
    <h2 class="text-xl font-bold mb-2">Print Test</h2>
    <p>This is a test component to verify print-color-adjust functionality.</p>
    <p class="mt-2">You should see:</p>
    <ul class="list-disc ml-4 mt-1">
      <li>Blue background</li>
      <li>White text</li>
      <li>Green border</li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PrintTest'
});
</script> 