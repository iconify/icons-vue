<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yx6ncrbik"/><path class="w8tf2lbwv"/><path class="vq0zfuqty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pelican" /></template>
<style>
.vq0zfuqty {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 13.5c1.5 1.75 3.5 2.75 6 2.75m-4 3v2m3-2v2M9.75 5h10.5c.6 0 .8.75.25 1.05l-5.75 3.2c-1.6.8-3.75.6-5-.25Z");
}

.w8tf2lbwv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 5.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yx6ncrbik {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3a2.5 2.5 0 0 0-2.5 2.5V13c0 3.75 2.5 6.25 6 6.25h3.5c3 0 5-1.5 6.5-4.25c-2.75-.5-5-1.75-7-3.75C12.5 10 11 9.5 9.75 9.5v-4A2.5 2.5 0 0 0 7.25 3");
}

</style>
