<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_1kxsbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:small-cell-pole" /></template>
<style>
.u_1kxsbwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3za2.5 2.5 0 0 1 2.5 2.5v1A2.5 2.5 0 0 1 12 9a2.5 2.5 0 0 1-2.5-2.5v-1A2.5 2.5 0 0 1 12 3m0 6v12.5m-3.5 0h7m.75-19a5.5 5.5 0 0 1 0 7");
}

</style>
