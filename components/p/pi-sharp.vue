<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjgsgebma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pi-sharp" /></template>
<style>
.vjgsgebma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.25h16.5m-11.5 0C8.75 11 7.75 15.5 5.5 19m9.75-13.75V16c0 2 .75 3 2.5 3h2.5v-2.5");
}

</style>
