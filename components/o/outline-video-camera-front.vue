<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cksk272yo"/><circle class="yzo5plbsh"/><path class="e5s4ytouy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-video-camera-front" /></template>
<style>
.cksk272yo {
  fill: currentColor;
  d: path("M18 10.48V6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-4.48l4 3.98v-11zm-2-.79V18H4V6h12z");
}

.e5s4ytouy {
  fill: currentColor;
  d: path("M14 15.43c0-.81-.48-1.53-1.22-1.85a6.95 6.95 0 0 0-5.56 0A2.01 2.01 0 0 0 6 15.43V16h8z");
}

.yzo5plbsh {
  cx: 10px;
  cy: 10px;
  r: 2px;
  fill: currentColor;
}

</style>
