<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl0ph99_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starry-sky-sharp" /></template>
<style>
.kl0ph99_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.62 4.32l.93 2.05l.38.82l.89.1l2.24.26l.9.1l-.67.6l-1.66 1.52l-.67.61l.18.88l.46 2.21l.18.88l-.79-.44l-1.96-1.12l-.78-.44l-.78.44l-1.96 1.12l-.79.44l.18-.88l.46-2.21l.18-.88l-.67-.61l-1.66-1.52l-.67-.6l.9-.1l2.24-.26l.89-.1l.38-.82l.93-2.05l.37-.82zm8.78 6.5l.49 1.02l.15.32l.35.04l1.13.15l.35.05l-.26.24l-.82.79l-.26.24l.07.34l.2 1.12l.07.34l-.31-.16l-1-.54l-.31-.17l-.31.17l-1 .54l-.31.16l.07-.34l.2-1.12l.07-.34l-.26-.24l-.82-.79l-.26-.24l.35-.05l1.13-.15l.35-.04l.15-.32l.49-1.02l.15-.32zm-.9-7.32l.24 1.76l1.76.24l-1.76.24l-.24 1.76l-.24-1.76l-1.76-.24l1.76-.24zM2.75 21.25c3-2.25 5.75-3.25 9-3.25s6.5 1 9.5 3.25");
}

</style>
