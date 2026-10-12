<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk1xsabdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:qalam-pen-sharp" /></template>
<style>
.gk1xsabdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 3.5L10.25 13.75m1.47 1.47l-2.94-2.94l-.53-.53l-.35.66l-3.8 7.18l-.35.66l.66-.35l7.18-3.8l.66-.35zM9.5 20.25c2.5-1.5 5 .75 7.5-.75l2-1.2l1.75.7");
}

</style>
