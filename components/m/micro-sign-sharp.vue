<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3caerv4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:micro-sign-sharp" /></template>
<style>
.o3caerv4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.75V16m0-6.75a3.5 3.5 0 0 0 7 0v-5.5m0 5.5V13h1.25M3.5 20.25h17m-17 0v-2m4.5 2V19m4 1.25v-2m4 2V19m4.5 1.25v-2");
}

</style>
