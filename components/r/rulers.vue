<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1sw5j1yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rulers" /></template>
<style>
.j1sw5j1yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.78 9.52L9.52 19.78q-1.41 1.41-2.82 0L4.22 17.3q-1.41-1.41 0-2.82L14.48 4.22q1.41-1.41 2.82 0l2.48 2.48q1.41 1.41 0 2.82m-6.54-4.06l2.47 2.47m-4.42-.53l1.59 1.59m-3.53.36l2.47 2.47m-4.42-.53l1.59 1.59m-3.53.36l2.47 2.47");
}

</style>
