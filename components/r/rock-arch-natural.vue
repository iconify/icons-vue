<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqgrsod8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rock-arch-natural" /></template>
<style>
.iqgrsod8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 20.5l1-10.5L7 5l6-1.5L18 5l3 4.5l.5 11h-5V15a4.5 4.5 0 0 0-9 0v5.5Zm4-11l3-2");
}

</style>
