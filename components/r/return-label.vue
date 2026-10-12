<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qqx19sbqz"/><path class="yr8i2u48m"/><path class="gdd8ehb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:return-label" /></template>
<style>
.gdd8ehb9d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 9.5h4.5a2.75 2.75 0 0 1 0 5.5H9m-.25-7.75L6.5 9.5l2.25 2.25");
}

.qqx19sbqz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25a1.5 1.5 0 0 1 1.5-1.5h10.3a1.5 1.5 0 0 1 1.17.56l4.16 5.2a2.4 2.4 0 0 1 0 3l-4.16 5.2a1.5 1.5 0 0 1-1.17.56H4.25a1.5 1.5 0 0 1-1.5-1.5Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yr8i2u48m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 12h.01");
}

</style>
