<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="z5puk737j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polar-flow" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z5puk737j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.8 21.458h18.478c2.688 0 2.688-4.443 0-4.443H9.248m-.023-.008c2.725-5.47 8.38-8.936 14.576-8.936c8.965 0 16.232 7.144 16.232 15.955S32.766 39.982 23.8 39.982S7.569 32.838 7.569 24.026c0-.861.071-1.722.213-2.572");
}

</style>
