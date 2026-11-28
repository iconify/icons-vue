<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="wxu-3obtm"/><path class="qv8l-xzcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:touchpad-mouse-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qv8l-xzcc {
  d: path("M11 16L2 16L2 2L20 2L20 7");
}

.wxu-3obtm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5355 21.5355C20.6318 22.4392 19.3804 23 18 23C15.2386 23 13 20.7614 13 18L13 14C13 11.2386 15.2386 9 18 9C20.7614 9 23 11.2386 23 14L23 18C23 19.3804 22.4392 20.6318 21.5355 21.5355ZM19 13L17 13L17 16L19 16Z");
  stroke: none;
}

</style>
