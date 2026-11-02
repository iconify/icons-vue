<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baixvqavh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call-fill-sharp" /></template>
<style>
.baixvqavh {
  fill: currentColor;
  d: path("M2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2C9.611 22 2 14.389 2 5m15.725-2.449A6.9 6.9 0 0 1 19.95 4.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-2 0a4.9 4.9 0 0 0-.393-1.946a5 5 0 0 0-1.071-1.59a5 5 0 0 0-1.59-1.071A4.9 4.9 0 0 0 15 4a1 1 0 0 1 0-2a6.9 6.9 0 0 1 2.725.551m-1.168 2.764c.476.2.907.491 1.271.857A3.98 3.98 0 0 1 19 9a1 1 0 0 1-2 0c0-.533-.207-1.039-.586-1.414A1.98 1.98 0 0 0 15 7a1 1 0 0 1 0-2a4 4 0 0 1 1.557.315");
}

</style>
