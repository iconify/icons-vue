<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7w_q0bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rugby-tackle" /></template>
<style>
.l7w_q0bnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 6.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m11 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M2.5 21.5c0-5 2-8 5.5-8c2 0 3.5 1 4 2.5c.5-1.5 2-2.5 4-2.5c3.5 0 5.5 3 5.5 8");
}

</style>
