<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ec2cnjd3y"/><path class="ztc14ryxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-off-duotone" /></template>
<style>
.ec2cnjd3y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.227 3.227A7 7 0 0 1 19 10q0 .92-.177 1.823Zm6.809 12.809C15.729 18.007 13.963 19.69 12 21c-3-2-7-6-7-11a6.98 6.98 0 0 1 1.575-4.425Z");
}

.ft5dv1b6b {
  fill: none;
}

.ztc14ryxt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.036 16.036C15.612 18.186 13.654 19.897 12 21c-3-2-7-6-7-11c0-1.678.59-3.219 1.575-4.425m3.652-2.348A7 7 0 0 1 19 10c0 .624-.062 1.232-.177 1.823M3 2l19 19");
}

</style>
