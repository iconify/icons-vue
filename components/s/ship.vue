<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcu2o8fyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ship" /></template>
<style>
.zcu2o8fyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12h16.5l-1.75 4.35a1.75 1.75 0 0 1-1.63 1.15H7.13a1.75 1.75 0 0 1-1.63-1.15Zm4 0V8.5A1.5 1.5 0 0 1 9.25 7h5.5a1.5 1.5 0 0 1 1.5 1.5V12M12 7V3.75M3 21c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
