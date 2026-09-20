<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avrskfcam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-off-24-regular" /></template>
<style>
.avrskfcam {
  fill: currentColor;
  d: path("M20.72 2.22a.75.75 0 1 1 1.06 1.06l-2.2 2.2A9.96 9.96 0 0 1 22 12c0 5.523-4.477 10-10 10a9.96 9.96 0 0 1-6.52-2.42l-2.2 2.2a.75.75 0 0 1-1.06-1.06zM6.543 18.517A8.5 8.5 0 0 0 18.517 6.543zm7.509-5.812c.282-.94 1.614-.94 1.896.001l.18.598a.85.85 0 0 0 .57.569l.598.18c.94.282.94 1.614 0 1.896l-.599.18a.85.85 0 0 0-.57.57l-.178.597c-.282.94-1.615.942-1.897 0l-.18-.599a.85.85 0 0 0-.57-.57l-.596-.178c-.94-.281-.941-1.614 0-1.896l.597-.18a.85.85 0 0 0 .57-.57zM12 2a9.95 9.95 0 0 1 5.298 1.52l-1.094 1.093a8.5 8.5 0 0 0-11.59 11.59L3.52 17.3A9.95 9.95 0 0 1 2 12C2 6.477 6.477 2 12 2M8.558 6.167c.314-.889 1.57-.89 1.885-.001l.46 1.295c.105.298.34.533.638.639l.87.307l-4.004 4.003l-.306-.869a1.05 1.05 0 0 0-.64-.64l-1.294-.458c-.889-.314-.889-1.571 0-1.885L7.461 8.1a1.05 1.05 0 0 0 .64-.64z");
}

</style>
