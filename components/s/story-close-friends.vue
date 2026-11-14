<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odkv4mb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:story-close-friends" /></template>
<style>
.odkv4mb1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 7.706 7.706m0 3.3a9.5 9.5 0 0 1-7.706 7.706m-3.3 0a9.5 9.5 0 0 1-7.706-7.706m0-3.3a9.5 9.5 0 0 1 7.706-7.706m2.4 5.481l.416 1.179a1.5 1.5 0 0 0 1.336.999l1.426.075a.829.829 0 0 1 .447 1.497l-1.039.762a1.5 1.5 0 0 0-.559 1.611l.37 1.331a.838.838 0 0 1-1.272.921l-1.043-.695a1.5 1.5 0 0 0-1.664 0l-1.043.695a.838.838 0 0 1-1.272-.921l.37-1.331a1.5 1.5 0 0 0-.559-1.611l-1.039-.762a.829.829 0 0 1 .447-1.497l1.426-.075a1.5 1.5 0 0 0 1.336-.999l.416-1.179a.795.795 0 0 1 1.5 0");
}

</style>
