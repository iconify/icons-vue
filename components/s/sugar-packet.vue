<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6augb1pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sugar-packet" /></template>
<style>
.j6augb1pb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 4l1-1l1 1l1-1l1 1l1-1l1 1l1-1l1 1v16l-1 1l-1-1l-1 1l-1-1l-1 1l-1-1l-1 1l-1-1Zm0 5.5h8m-8 5h8");
}

</style>
