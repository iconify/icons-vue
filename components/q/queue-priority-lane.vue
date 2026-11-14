<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj5epw6jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:queue-priority-lane" /></template>
<style>
.nj5epw6jg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4h11.116a1.75 1.75 0 0 1 1.121.406l2.4 2a1.75 1.75 0 0 1 0 2.688l-2.4 2a1.75 1.75 0 0 1-1.121.406H4.75A1.75 1.75 0 0 1 3 9.75v-4A1.75 1.75 0 0 1 4.75 4M3 15.5h18M3 20h18");
}

</style>
