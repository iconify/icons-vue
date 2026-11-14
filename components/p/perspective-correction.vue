<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbkou2b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:perspective-correction" /></template>
<style>
.nbkou2b_r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.209 20.329q.75.921 1.938.921h13.706q1.188 0 1.938-.921q.75-.92.511-2.083l-2.779-13.5q-.411-1.996-2.449-1.996H7.926q-2.038 0-2.449 1.996l-2.779 13.5q-.239 1.163.511 2.083M10.5 6.25h3q2.25 0 2.25 2.25V16q0 2.25-2.25 2.25h-3q-2.25 0-2.25-2.25V8.5q0-2.25 2.25-2.25");
}

</style>
