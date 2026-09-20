<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkje5bbsk"/><path class="eud-3ptuk"/><path class="owdk3hf1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:share-favorite-outline-thin" /></template>
<style>
.eud-3ptuk {
  d: path("M15 12h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkje5bbsk {
  d: path("M2 9a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0l-5 5Z");
}

.owdk3hf1a {
  d: path("m18 8 4 4 -4 4");
}

</style>
