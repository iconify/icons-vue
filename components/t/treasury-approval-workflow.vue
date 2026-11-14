<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1hq90blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-approval-workflow" /></template>
<style>
.e1hq90blb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.364 2.808l2.828 2.828l-9.899 9.9l-3.889 1.06l1.06-3.889Zm-9.9 9.899l2.829 2.829M14.75 18l2 2L21 15.75");
}

</style>
