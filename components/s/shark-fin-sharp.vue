<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-662bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shark-fin-sharp" /></template>
<style>
.ye-662bze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 15c2.5-3.25 4-7.5 3.75-11.25V2.583l1 .417c4 1.75 7.25 6.25 8 12Zm-2.75 3.25c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75m-15 3.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>
