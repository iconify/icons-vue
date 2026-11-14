<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcg8evbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mineral-sample" /></template>
<style>
.hcg8evbbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 20.5V8L12 4l2.5 4v12.5m-6.75 0l-3.5-6l.25-3.75l3.25 1.75l1.75 3m6.75 5l3.5-6l-.25-3.75l-3.25 1.75l-1.75 3m-11 5h17");
}

</style>
