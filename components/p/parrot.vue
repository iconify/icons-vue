<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zc9fx0bvt"/><path class="lmo5kobac"/><path class="scu5sqbgh"/><path class="iwnim1b6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parrot" /></template>
<style>
.iwnim1b6d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 11.5c.25 2 1.25 3.5 3 4.25");
}

.lmo5kobac {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.85 6.6c2.6.4 4.4 2.4 4.4 4.9c0 1.1-.35 2.1-.95 2.85c-.45-1.4-1.6-2.35-3.3-3.1");
}

.scu5sqbgh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 7.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zc9fx0bvt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 3.25a4.5 4.5 0 0 1 4.5 4.5v3.5c0 3.75-2 6.5-5 7.75l-1.25 2.25h-2.5l1-3c-1.75-1.5-2.5-3.75-2.5-6.25V9a5.75 5.75 0 0 1 5.75-5.75");
}

</style>
