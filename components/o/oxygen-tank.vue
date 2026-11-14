<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcnlc96qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oxygen-tank" /></template>
<style>
.jcnlc96qe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11a4.5 4.5 0 0 1 9 0v8.5a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2ZM12 6.5v-3m-2.5 0h5m-7 9.5h9");
}

</style>
