<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8v023bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vaccine-syringe" /></template>
<style>
.k8v023bec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.99 9.525L9.525 5.99l7.071 7.071l-3.535 3.535Zm-1.061 1.061l5.657-5.657m-5.304.353l2.475 2.475m-3.889-1.06l2.829-2.829m8.131 10.96l3.89 3.89M8.111 11.646l1.414-1.414m.707 3.536l1.414-1.414");
}

</style>
