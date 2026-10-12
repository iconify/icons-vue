<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hdc4v-bjz"/><path class="vqih-ynua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pendant-light" /></template>
<style>
.hdc4v-bjz {
  d: path("M12 2.75v7m-3.75 0h7.5l4 6.5a.65.65 0 0 1-.55 1H4.8a.65.65 0 0 1-.55-1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqih-ynua {
  d: path("M9.75 17.25a2.25 2.25 0 0 0 4.5 0Z");
}

</style>
