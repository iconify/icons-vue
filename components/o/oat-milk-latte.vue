<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axw0kobyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oat-milk-latte" /></template>
<style>
.axw0kobyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.389 13.709q-.258.191-.542.339t-.589.249t-.621.152T10 14.5H7q-.197 0-.392-.019q-.196-.02-.388-.058q-.193-.038-.381-.095t-.37-.132q-.181-.076-.355-.168q-.173-.093-.336-.202t-.316-.234q-.151-.125-.29-.264t-.264-.29t-.234-.316q-.109-.163-.202-.336q-.092-.174-.168-.355q-.075-.182-.132-.37t-.095-.381t-.058-.388T3 10.5V3h11v7.5q0 .318-.05.631q-.05.314-.149.615q-.099.302-.244.584q-.146.283-.334.539M14 5h1a2.5 2.5 0 0 1 0 5h-1m4 4v7.5m-2.5-4L18 20l2.5-2.5m-5-3L18 17l2.5-2.5");
}

</style>
