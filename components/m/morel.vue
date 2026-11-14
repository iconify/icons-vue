<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-zxb2byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:morel" /></template>
<style>
.o-zxb2byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5C18.5 5 19 12 17.5 15h-11C5 12 5.5 5 12 2.5ZM9.5 15v6.5h5V15M10 7v5.5M14 7v5.5");
}

</style>
