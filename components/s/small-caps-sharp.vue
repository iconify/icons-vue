<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9-rthb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:small-caps-sharp" /></template>
<style>
.q9-rthb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 19.25l5-14.5l5 14.5m-8.25-5H11m3 5l3.5-9l3.5 9m-5.9-2.75h4.8");
}

</style>
