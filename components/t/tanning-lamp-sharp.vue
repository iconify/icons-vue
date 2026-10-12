<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjnzgj9cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tanning-lamp-sharp" /></template>
<style>
.vjnzgj9cx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75H17l.63 1.08l2.24 3.84l.63 1.08h-17l.63-1.08l2.24-3.84L7 2.75zm-1 3h9.5M7 11.5l-1 2.25m6-2.25V14m5-2.5l1 2.25M2.75 17.5h18.5v3.75H2.75z");
}

</style>
