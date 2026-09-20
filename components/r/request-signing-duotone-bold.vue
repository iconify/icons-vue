<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="q8cjcf-8e"/><path class="abnm6smsv"/><path class="mfc7nxp-y"/><path class="gb580sbiw"/><path class="ayabppr3a"/><path class="q829csbzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:request-signing-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.ayabppr3a {
  d: path("M12 14.5V17");
}

.gb580sbiw {
  d: path("M10 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.q829csbzu {
  d: path("M12 15.5h2.5");
}

.q8cjcf-8e {
  fill: currentColor;
  d: path("M10 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
