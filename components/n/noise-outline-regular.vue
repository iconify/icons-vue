<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lu0ovacdk"/><path class="qpa6yacba"/><path class="k8_np0a0y"/><path class="asewlgb2k"/><path class="s4ceatb9m"/><path class="tr__z6b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:noise-outline-regular" /></template>
<style>
.asewlgb2k {
  d: path("M6 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k8_np0a0y {
  d: path("M17 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lu0ovacdk {
  d: path("M4 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qpa6yacba {
  d: path("M10 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s4ceatb9m {
  d: path("M13 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.tr__z6b9j {
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
