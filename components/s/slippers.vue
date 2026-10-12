<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4w7ko9oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slippers" /></template>
<style>
.s4w7ko9oc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 20.25H18.5a2.75 2.75 0 0 0 2.75-2.75c0-3.5-2.5-5.75-5.75-5.75c-2.5 0-4 1.25-5.25 3q-1.125 1.5-3 1.5h-2.5a2 2 0 0 0 0 4m6-3h8");
}

</style>
