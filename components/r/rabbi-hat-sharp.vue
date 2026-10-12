<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysd9cctig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rabbi-hat-sharp" /></template>
<style>
.ysd9cctig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.75V6.5c0-2 2-3.75 5-3.75s5 1.75 5 3.75v4.25ZM7 8.5h10m-14.25 4c0-1 4.15-1.75 9.25-1.75s9.25.75 9.25 1.75s-4.15 1.75-9.25 1.75s-9.25-.75-9.25-1.75Zm4.75 3.25c-.75 1 .75 1.75 0 2.75s.75 1.75 0 2.75m9-5.5c.75 1-.75 1.75 0 2.75s-.75 1.75 0 2.75");
}

</style>
