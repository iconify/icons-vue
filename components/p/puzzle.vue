<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2vum83vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle" /></template>
<style>
.f2vum83vf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 7h3a2 2 0 0 1 2 2v3a2.236 2.236 0 1 0 0 4v3a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-3a2.236 2.236 0 1 1 0-4V9a2 2 0 0 1 2-2h3a2.236 2.236 0 1 1 4 0");
}

</style>
