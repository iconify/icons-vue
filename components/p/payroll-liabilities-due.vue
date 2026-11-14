<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkj8bhboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payroll-liabilities-due" /></template>
<style>
.hkj8bhboh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 18.5H2.5v-13h19v13h-.7M6 9.5h5.5m-5.5 5h3.5m8.5.25v3.5M18 21h.01");
}

</style>
