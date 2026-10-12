<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hsp0kr76n"/><path class="b1l6vhbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palette" /></template>
<style>
.b1l6vhbgz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 12.5h.01M8.5 8h.01m3.99-1.5h.01m3.99 1.75h.01");
}

.hsp0kr76n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 0 0 0 18.5c1.1 0 1.75-.75 1.75-1.65c0-.45-.2-.85-.45-1.2c-.3-.35-.5-.75-.5-1.2c0-.95.75-1.7 1.7-1.7h2a5.25 5.25 0 0 0 4.75-5.25c0-3.85-4.15-7.5-9.25-7.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
