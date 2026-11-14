<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn1k__jcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-sparkle" /></template>
<style>
.qn1k__jcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.762 5.651A5.3 5.3 0 0 0 9.5 7C8 5.5 5.75 5 4.25 6c-1.75 1.25-1.5 4-.75 6.5c.75 2.25 1 4.5 1.75 7.25c.5 1.75 2 1.75 2.5 0l.75-3.5c.25-1 1.75-1 2 0l.75 3.5c.5 1.75 2 1.75 2.5 0c.75-2.75 1-5 1.75-7.25c.128-.427.242-.861.333-1.294M18 2.5q.5 3 3.5 3.5q-3 .5-3.5 3.5q-.5-3-3.5-3.5q3-.5 3.5-3.5");
}

</style>
