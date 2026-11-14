<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofs1b3ctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repo-archived" /></template>
<style>
.ofs1b3ctu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 8.5l2.5-5h11l2.5 5M12.1 19H3V8.5h16v3.2m-8-8.2v5m7 6V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
