<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w21v8jiey"/><path class="kc2e0qvxl"/><path class="cfd43lbgp"/><path class="utcr20lug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:roof-duotone-bold" /></template>
<style>
.cfd43lbgp {
  d: path("M7 13h10");
}

.kc2e0qvxl {
  d: path("M2 18 12 8l10 10Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.utcr20lug {
  d: path("M12 13v5");
}

.w21v8jiey {
  fill: currentColor;
  d: path("M2 18 12 8l10 10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
