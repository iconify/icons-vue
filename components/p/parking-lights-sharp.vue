<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd484acoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parking-lights-sharp" /></template>
<style>
.kd484acoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 8.5h.25a3.5 3.5 0 0 1 0 7h-.25Zm-2.5 0h-.25a3.5 3.5 0 0 0 0 7h.25ZM19 12h2.25m-2.5-3.25l2-1.25m-2 7.75l2 1.25M5 12H2.75m2.5-3.25l-2-1.25m2 7.75l-2 1.25");
}

</style>
