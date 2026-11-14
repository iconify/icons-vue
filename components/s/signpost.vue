<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi463f5co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signpost" /></template>
<style>
.zi463f5co {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 5h10.025a1.75 1.75 0 0 1 1.238.513l.75.75a1.75 1.75 0 0 1 0 2.474l-.75.75a1.75 1.75 0 0 1-1.238.513H6.75A1.75 1.75 0 0 1 5 8.25v-1.5A1.75 1.75 0 0 1 6.75 5m10.5 7.5H7.225a1.75 1.75 0 0 0-1.238.513l-.75.75a1.75 1.75 0 0 0 0 2.474l.75.75a1.75 1.75 0 0 0 1.238.513H17.25A1.75 1.75 0 0 0 19 15.75v-1.5a1.75 1.75 0 0 0-1.75-1.75M12 2.5V5m0 5v2.5m0 5v4");
}

</style>
