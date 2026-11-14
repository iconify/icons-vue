<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ytr0brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:watering-can-pouring" /></template>
<style>
.t_ytr0brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h10v11H3Zm2 0V6.5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2V9m2 7l6-7.5M17.5 7l3 3m.5 3.5h.01m-2.01 3h.01");
}

</style>
