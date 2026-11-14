<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o54x0nuni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potted-herb" /></template>
<style>
.o54x0nuni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.741 14.5h8.518a1.75 1.75 0 0 1 1.697 2.174l-.875 3.5a1.75 1.75 0 0 1-1.697 1.326H8.616a1.75 1.75 0 0 1-1.697-1.326l-.875-3.5A1.75 1.75 0 0 1 7.741 14.5m4.259 0V7m0 0c-1.75-1.5-1.75-3.25 0-4.5c1.75 1.25 1.75 3 0 4.5m0 2.5C9 8 6 8.5 4.5 11c2.5 1 5.5.5 7.5-1.5m0 0c3-1.5 6-1 7.5 1.5c-2.5 1-5.5.5-7.5-1.5");
}

</style>
