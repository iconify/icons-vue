<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkbpux9zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-follower-line" /></template>
<style>
.zkbpux9zo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M8.5 21.5c0-3.25 3-5.25 6.5-5.25s6.5 2 6.5 5.25M4.25 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M2.5 15c0-2.5 2-4 4.5-4c.75 0 1.5.25 2 .5m-6.5 6.75h3m-3 3.25H5");
}

</style>
