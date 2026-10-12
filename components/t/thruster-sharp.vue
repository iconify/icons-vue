<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tij8z5b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thruster-sharp" /></template>
<style>
.tij8z5b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.66 8.58l5.18-2.41l.91-.42v12.5l-.91-.42l-5.18-2.41l-.91-.42V9zm9.09-.08h2.5m3.5 0h2.5m-8.5 3.5h8.5m-8.5 3.5h2.5m3.5 0h2.5");
}

</style>
