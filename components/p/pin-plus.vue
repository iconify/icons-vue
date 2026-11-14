<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq6s5hb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-plus" /></template>
<style>
.qq6s5hb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.5h.5a1.75 1.75 0 0 1 1.75 1.75v2.22a1.75 1.75 0 0 0 .294.971L13 10.25a1.447 1.447 0 0 1-1.204 2.25H7.204A1.447 1.447 0 0 1 6 10.25l1.206-1.809A1.75 1.75 0 0 0 7.5 7.47V5.25A1.75 1.75 0 0 1 9.25 3.5m.25 9V20m8.5-5v6m-3-3h6");
}

</style>
