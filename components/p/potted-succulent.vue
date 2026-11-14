<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd6b4kbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potted-succulent" /></template>
<style>
.jd6b4kbah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.741 14.5h8.518a1.75 1.75 0 0 1 1.697 2.174l-.875 3.5a1.75 1.75 0 0 1-1.697 1.326H8.616a1.75 1.75 0 0 1-1.697-1.326l-.875-3.5A1.75 1.75 0 0 1 7.741 14.5m4.259 0C9.5 12 9.5 8 12 4.5c2.5 3.5 2.5 7.5 0 10m-1 0c-4 0-6.5-2.5-7-6c3.5.5 6 2.5 7 6m2 0c4 0 6.5-2.5 7-6c-3.5.5-6 2.5-7 6");
}

</style>
