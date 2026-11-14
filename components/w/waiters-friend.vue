<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4wss-31o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waiters-friend" /></template>
<style>
.q4wss-31o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8h14.5A1.75 1.75 0 0 1 21 9.75a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 9.75A1.75 1.75 0 0 1 4.75 8M12 11.5l1.75 1.5l-3.5 2l3.5 2l-3.5 2L12 20.5M4.75 8l3.5-3.5");
}

</style>
