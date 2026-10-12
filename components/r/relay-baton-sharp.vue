<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lemq9kjtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:relay-baton-sharp" /></template>
<style>
.lemq9kjtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.75h13.25v6.5H8zm4.25 0v6.5M17 8.75v6.5m-14.25-5H5m-2.25 3.5H5");
}

</style>
