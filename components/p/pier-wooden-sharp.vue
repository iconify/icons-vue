<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zir0nzxlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pier-wooden-sharp" /></template>
<style>
.zir0nzxlz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h18.5v3.5H2.75zm6 0v3.5m6.5-3.5v3.5m-9.75 0v10.5m6.5-10.5v10.5m6.5-10.5v10.5m-15.75-5c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>
