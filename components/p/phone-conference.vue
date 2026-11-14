<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r34gvr92q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:phone-conference" /></template>
<style>
.r34gvr92q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 8.75c.5 0 1 .25 1 1L8 12c0 .5-.25 1-.75 1.25l-1 .75c1 2 1.75 2.75 3.75 3.75l.75-1.25c.25-.25.75-.5 1.25-.5l2.25.5c.5.25 1 .75 1 1.25V20c0 .75-.75 1.5-1.5 1.5c-6 0-11.25-5.25-11.25-11.25c0-.75.75-1.5 1.5-1.5ZM13.75 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.5 6c0-1.75 1.5-3 3.25-3s3.25 1.25 3.25 3m.125-8.766a1.75 1.75 0 0 1 1.75 3.032M20 6.75c1 .5 1.5 1.5 1.5 2.75");
}

</style>
