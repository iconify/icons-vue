<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jvkldmbno"/><path class="yfgzlm35n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swastika-hindu" /></template>
<style>
.jvkldmbno {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.75v16.5M3.75 12h16.5M12 3.75h8.25m0 8.25v8.25m-8.25 0H3.75m0-8.25V3.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yfgzlm35n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 7.75h.01m8.49 0h.01m-8.51 8.5h.01m8.49 0h.01");
}

</style>
