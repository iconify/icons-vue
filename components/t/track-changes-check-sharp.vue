<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj8vh7bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:track-changes-check-sharp" /></template>
<style>
.rj8vh7bib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 5.25h13M7.25 12h5m5.5 0h2.5m-13 6.75h10M3.75 9v6m9.5.5L15.5 11l2.25 4.5");
}

</style>
