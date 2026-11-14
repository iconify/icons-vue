<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_52dd7gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:opening-act" /></template>
<style>
.a_52dd7gl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19m-19 0h4q0 8-4 11.5Zm19 0h-4q0 8 4 11.5ZM3 20.5h18m-9-15zA2.5 2.5 0 0 1 14.5 8v3a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 11V8A2.5 2.5 0 0 1 12 5.5m0 8v7");
}

</style>
