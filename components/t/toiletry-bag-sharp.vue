<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3c6l-b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toiletry-bag-sharp" /></template>
<style>
.i3c6l-b9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 9.25L7.25 3.5m6.25 1.25h4v4.5h-4zM2.75 9.25h18.5v12H2.75zm0 3.5h18.5");
}

</style>
