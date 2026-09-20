<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kugyihn3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:puzzle-piece-outline-bold" /></template>
<style>
.kugyihn3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M4 4h6c0 -1.5 4 -1.5 4 0h6v6c1.5 0 1.5 4 0 4v6H4v-6c1.5 0 1.5 -4 0 -4Z");
}

</style>
