<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq9xj0bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:password-reveal" /></template>
<style>
.jq9xj0bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19v8h-19Zm5 4h.01m4.49 0h.01m4.49 0h.01M5.5 17.25C7 15 9.25 13.75 12 13.75s5 1.25 6.5 3.5c-1.5 2.25-3.75 3.5-6.5 3.5s-5-1.25-6.5-3.5Zm6.5 0h.01");
}

</style>
