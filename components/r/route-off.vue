<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3j0-7abu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-off" /></template>
<style>
.u3j0-7abu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 18.5h6.1m-6.088-6.034q-.142-.02-.282-.052q-.14-.031-.277-.074t-.27-.097t-.261-.119t-.25-.14t-.239-.159q-.116-.085-.224-.179q-.109-.094-.209-.197q-.1-.102-.192-.212q-.092-.111-.174-.228q-.083-.118-.155-.242q-.073-.124-.135-.253q-.062-.13-.113-.264t-.091-.271q-.041-.138-.069-.279t-.046-.283M9.4 5.5h6.1m-12 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-12-2l17 17");
}

</style>
