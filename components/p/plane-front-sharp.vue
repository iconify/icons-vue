<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyx8d9bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plane-front-sharp" /></template>
<style>
.dyx8d9bjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75h1.75v6.5L20.1 13l.392.207l.008.443v.95l.004.686l-.654-.206l-6.1-1.83v4.25l1.85 1.4l.3.225V20.3l-.005.691l-.655-.221L12 19.75l-3.24 1.02l-.655.221L8.1 20.3v-1.175l.3-.225l1.85-1.4v-4.25l-6.1 1.83l-.654.206l.004-.686v-.95l.008-.443L3.9 13l6.35-3.75v-6.5z");
}

</style>
