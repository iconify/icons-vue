<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdywfmb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:screwdriver-sharp" /></template>
<style>
.tdywfmb4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.38 9.62h0l.89.88l-.27 2.03l-.26 2.03l-2.12 2.12l-2.3 2.3L8.2 21.1l-2.12-2.12l-1.06-1.06L2.9 15.8l2.12-2.12l2.3-2.3l2.12-2.12L11.47 9l2.03-.27zM11.2 12.8l-3.53 3.53M21.1 2.9l-6.71 6.71");
}

</style>
