<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="brep0141e"/><path class="a5gfiqnry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-duotone" /></template>
<style>
.a5gfiqnry {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 15l-5.293 5.293c-.206.206-.553.015-.49-.27l1.566-7.047A.802.802 0 0 0 8 12H7a.65.65 0 0 1-.594-.914l3.33-7.492A1 1 0 0 1 10.65 3H16a.58.58 0 0 1 .504.868l-3.008 5.264A.58.58 0 0 0 14 10h3c.369 0 .554.446.293.707z");
}

.brep0141e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13 15l-5.293 5.293a.291.291 0 0 1-.49-.269l1.566-7.048A.803.803 0 0 0 8 12H7a.65.65 0 0 1-.594-.914l3.33-7.492c.161-.361.519-.594.914-.594H16a.58.58 0 0 1 .504.868l-3.008 5.264A.58.58 0 0 0 14 10h3a.414.414 0 0 1 .293.707Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
