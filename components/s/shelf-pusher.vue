<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfl9t3rns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shelf-pusher" /></template>
<style>
.hfl9t3rns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 16.5h16a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 18A1.5 1.5 0 0 1 4 16.5m7.75-9h5a1.75 1.75 0 0 1 1.75 1.75v5.5a1.75 1.75 0 0 1-1.75 1.75h-5A1.75 1.75 0 0 1 10 14.75v-5.5a1.75 1.75 0 0 1 1.75-1.75m-5.25 0v9m0-4.5H10M3 3.5h11M11.5 2L14 3.5L11.5 5");
}

</style>
