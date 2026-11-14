<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abrjikh2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-broadcast-tower" /></template>
<style>
.abrjikh2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 21.5l4.5-13l4.5 13M12 3v5.5M8.75 4.25a4 4 0 0 0 0 4.5M6.25 2.5a7 7 0 0 0 0 8m9-6.25a4 4 0 0 1 0 4.5m2.5-6.25a7 7 0 0 1 0 8");
}

</style>
