<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp222cbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mushroom-farm" /></template>
<style>
.fp222cbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13.5a2.5 2.5 0 0 1 5 0ZM8 10a4 4 0 0 1 8 0Zm7.75 3.5a2.5 2.5 0 0 1 5 0Zm-10 3v4.75M12 13v8.25m6.25-4.75v4.75M2.75 18v2A1.25 1.25 0 0 0 4 21.25h16A1.25 1.25 0 0 0 21.25 20v-2");
}

</style>
