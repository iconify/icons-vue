<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="gw7tcmbww"/><path class="xmeohhb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:newdays" /></template>
<style>
.gw7tcmbww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.521 21.65l.758-8l4.542 8l.758-8m14.599 2.7l-1.65 5.3l-1.65-5.3l-1.65 5.3l-1.65-5.3m4.675 14.853c.365.307.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325S35.077 29 34.347 29h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447m-7.285 4.853l-2.131-5.3m4 0l-2.54 7.2a1.2 1.2 0 0 1-1.131.8h-.329m-13.796-10.7h2.8c1.933 0 3.351 1.567 3.168 3.5l-.094 1c-.184 1.933-1.899 3.5-3.832 3.5h-1.8l.758-8m11.985-3.009a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0V19h-4m2.545 10.65c0 1.105-.889 2-1.985 2h-.696c-.727 0-1.315-.593-1.315-1.325S20.715 29 21.442 29h2.685");
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

.xmeohhb_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.627 26.875c.482-.483.82-.525 1.75-.525c1.056 0 1.75.465 1.75 1.72v3.58m10.051-17.3c-1.16.67-4.14.4-5.633 0s-4.474-.67-5.634 0");
}

</style>
