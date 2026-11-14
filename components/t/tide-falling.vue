<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqwlcdbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tide-falling" /></template>
<style>
.rqwlcdbmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 21.5h18m-9-19V11M8.5 7.5L12 11l3.5-3.5");
}

</style>
