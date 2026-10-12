<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xeo0s3b4g"/><path class="dcnzi9b5t"/><path class="ibr467p7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocket-launch" /></template>
<style>
.dcnzi9b5t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.25h.01");
}

.ibr467p7b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 21.25A2.5 2.5 0 0 1 6 17.75a3.25 3.25 0 0 1 6-1a3.25 3.25 0 0 1 6 1a2.5 2.5 0 0 1 2.75 3.5Z");
}

.xeo0s3b4g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c2.25 1.75 3.5 4 3.5 6.75l2 1.5v1.75l-2-.75h-7l-2 .75V11l2-1.5c0-2.75 1.25-5 3.5-6.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
