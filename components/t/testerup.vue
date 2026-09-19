<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gc39j-bnl"/><path class="zztbbm4jq"/><path class="nx6c2qbta"/><path class="zli6ujbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:testerup" /></template>
<style>
.gc39j-bnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.501 31.916H11.926A6.42 6.42 0 0 1 5.5 25.475v-9.018a6.42 6.42 0 0 1 6.426-6.442h20.563a6.42 6.42 0 0 1 6.425 6.442v1.596");
}

.nx6c2qbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.95 27.705l.065-3.222l13.598 13.502L42.5 24.129v-9.7l-4.715-1.63");
}

.zli6ujbje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 14.43L28.726 28.35l-3.65-3.932l-10.06.065");
}

.zztbbm4jq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.26 27.705h-5.656a1.284 1.284 0 0 1-1.286-1.288V17.49c0-.714.574-1.289 1.286-1.289h19.128c.712 0 1.285.575 1.285 1.289v6.523");
}

</style>
