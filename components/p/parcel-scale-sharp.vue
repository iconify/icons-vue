<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it51898yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parcel-scale-sharp" /></template>
<style>
.it51898yf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 4h10.5v8.25H6.75zM12 4v3m-7.25 7.5h14.5m-7.25 0v2.25m-9.25 0h18.5v4.5H2.75zM15.5 19H18");
}

</style>
