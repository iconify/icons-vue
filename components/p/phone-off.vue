<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1ig8ebso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:phone-off" /></template>
<style>
.d1ig8ebso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.471 3.5H8.5c.8 0 1.3.5 1.5 1.25l.448 1.792m6.992 7.006l1.81.452c.75.2 1.25.7 1.25 1.5v1.082m-4.049 3.765C10.03 19.385 4.644 14.012 3.66 7.596M3.5 3.5l17 17");
}

</style>
