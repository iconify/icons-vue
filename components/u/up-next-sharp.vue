<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lady6yb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:up-next-sharp" /></template>
<style>
.lady6yb7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h16.5m-16.5 5h16.5m-8 7.5h8M4.59 14.54l3.32 2.17l.84.54l-.84.54l-3.32 2.17l-.84.54V14z");
}

</style>
