<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r5yow129w"/><circle class="cpk0fnbgt"/><path class="t5kliwbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nfcreader" /></template>
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

.r5yow129w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 15.7a3.76 3.76 0 0 1 2.8 2.5m-2.5-5.8c2.8.7 4.6 2.6 5.8 5.3m-5.1-8.9c3.4.9 6.6 2.7 8.6 8.3M12.3 35.3a3.76 3.76 0 0 1 2.8 2.5M12.6 32c2.8.7 4.6 2.6 5.8 5.3m-5.1-8.9c3.4.9 6.6 2.7 8.6 8.3");
}

.t5kliwbnd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.8 18.2h5.7M22.8 24h3.7m-3.7-5.8v11.6M11.1 24V12.4L18.7 24V12.4m18.2 19.3a3.82 3.82 0 0 1-3.8 3.9h0a3.8 3.8 0 0 1-3.8-3.8v-3.9a3.8 3.8 0 0 1 3.8-3.8h0a3.8 3.8 0 0 1 3.8 3.8h0");
}

</style>
