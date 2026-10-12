<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuvi0najb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:picnic-basket-sharp" /></template>
<style>
.vuvi0najb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11.5a5.75 5.75 0 0 1 11.5 0M4 11.5h17.25L21 12.72l-1.5 7.31l-.25 1.22H4.75l-.25-1.22L3 12.72l-.25-1.22zm-.58 3.25h17.16M4.08 18h15.84");
}

</style>
