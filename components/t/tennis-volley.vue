<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2_r94jas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-volley" /></template>
<style>
.a2_r94jas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5a4.5 6.25 0 1 0 9 0a4.5 6.25 0 1 0-9 0Zm7.25 2.75L21 19.5m-18.5-1a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7.818 6.318l6.364 6.364");
}

</style>
