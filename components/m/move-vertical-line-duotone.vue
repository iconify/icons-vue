<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jp1ilnbst"/><path class="x07ftrzei"/><path class="w4qe5y36z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-vertical-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jp1ilnbst {
  d: path("M12 22.1422L12.0001 1.85791");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w4qe5y36z {
  stroke-linejoin: round;
  d: path("M16.1417 18.0005L12 22.1421L7.85841 18.0005");
}

.x07ftrzei {
  stroke-linejoin: round;
  d: path("M16.1417 5.99954L12 1.85791L7.85841 5.99954");
}

</style>
