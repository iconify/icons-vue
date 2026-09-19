<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cmtryccqs"/><circle class="cpk0fnbgt"/><path class="ws6ddwbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zing-mp3" /></template>
<style>
.cmtryccqs {
  cx: 24px;
  cy: 24px;
  r: 4.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ws6ddwbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.875 19.901L18.31 3.258m11.38 41.484l-4.565-16.643m-5.224-2.974L3.258 29.69m41.484-11.38l-16.643 4.565");
}

</style>
