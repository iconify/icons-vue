<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5qjvlbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipette" /></template>
<style>
.k5qjvlbhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.428 4.34za2.25 2.25 0 0 1 .277 3.169l-.964 1.149a2.25 2.25 0 0 1-3.17.278a2.25 2.25 0 0 1-.277-3.17l.964-1.149a2.25 2.25 0 0 1 3.17-.277M14.25 9.319za1.25 1.25 0 0 1 .154 1.761l-4.789 5.707a1.5 1.5 0 0 1-.459.368l-1.177.609a.677.677 0 0 1-.957-.803l.395-1.265a1.5 1.5 0 0 1 .283-.516l4.789-5.707a1.25 1.25 0 0 1 1.761-.154M11.952 7.39l4.596 3.857");
}

</style>
