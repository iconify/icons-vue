<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmver2tym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tetrahedron-sharp" /></template>
<style>
.rmver2tym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.72 3.77l7.81 10.96l.72 1.02l-1.01.74l-5.48 4.02l-1.01.74l-1.15-.5L3.9 17l-1.15-.5l.7-1.04L11.3 3.79l.7-1.04zm-.42 2.48l1.45 15");
}

</style>
