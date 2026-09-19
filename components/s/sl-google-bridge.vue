<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="flukab_vt"/><path class="h9p85f3ya"/><path class="q7bna07rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sl-google-bridge" /></template>
<style>
.flukab_vt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 32.598c3.627 0 4.048-1.682 5.73-4.374s3.415-5.54 4.436-7.233c.783-1.297 1.435-2.103 2.81-2.103c1.597 0 2.175.252 3.605 2.103c-2.271-4.206-4.753-5.594-8.285-5.594s-6.014 1.388-8.285 5.594");
}

.h9p85f3ya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.907 23.889s1.623 2.555 3.074 4.931s3.133 3.778 7.019 3.778c3.627 0 5.489-1.682 7.17-4.374s3.416-5.54 4.437-7.233c.782-1.297 1.435-2.103 2.809-2.103c1.43 0 2.61.827 4.084 2.488c-2.935-4.92-5.23-5.979-8.764-5.979s-5.673 1.185-8.47 5.453l-1.808 2.96");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.q7bna07rz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.77 24v.01c.35.54 1.75 2.74 3.01 4.81c1.28 2.1 2.73 3.43 5.72 3.72M22.08 20.99c1.588 3.057 3.334 7.956 6.299 7.956c.931 0 1.9-.305 2.791-.724");
}

</style>
