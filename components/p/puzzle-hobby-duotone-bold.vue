<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wmlzbnb0j"/><path class="zlfbc7lss"/><path class="qmonhebui"/><path class="zmangp7gz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:puzzle-hobby-duotone-bold" /></template>
<style>
.qmonhebui {
  d: path("M3 4h6c0 -1.5 4 -1.5 4 0v6H3Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wmlzbnb0j {
  fill: currentColor;
  d: path("M3 4h6c0 -1.5 4 -1.5 4 0v6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zlfbc7lss {
  fill: currentColor;
  d: path("M11 13h10v6c0 1.5 -4 1.5 -4 0h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zmangp7gz {
  d: path("M11 13h10v6c0 1.5 -4 1.5 -4 0h-6Z");
}

</style>
