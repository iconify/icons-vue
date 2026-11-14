<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fagxtxbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stone-wall" /></template>
<style>
.fagxtxbcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 3l7.5-.25l.25 5l-8 .25Zm10.5-.25l7.5.5l.25 4.75l-8-.25Zm-9 8l15-.25l.25 3.75l-15.5.25ZM3 17.25l7.5-.25l.25 4l-8 .25ZM13.5 17l7.75.25L21 21l-7.75.25Z");
}

</style>
