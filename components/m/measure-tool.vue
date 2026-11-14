<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3ekzbc4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measure-tool" /></template>
<style>
.j3ekzbc4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h19v6h-19Zm4 0V17m4-2.5v1.75m4-1.75V17m4-2.5v1.75M2.5 8h19m-19-2.5v5m19-5v5");
}

</style>
