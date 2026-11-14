<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbe8fqblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-audit-trail" /></template>
<style>
.cbe8fqblf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0M6 7v3m0 4v3m4.5-12H12m2.5 0h6m-10 7H12m2.5 0h4m-8 7H12m2.5 0H17");
}

</style>
