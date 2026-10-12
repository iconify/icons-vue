<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6q3e5bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:percent-bar-sharp" /></template>
<style>
.p6q3e5bgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h11v5h-11zm13.5 0h5v5h-5zm-13.5 9.5h6.5v5h-6.5zm9 0h9.5v5h-9.5z");
}

</style>
