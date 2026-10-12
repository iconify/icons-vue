<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmvrygbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-to-speech-sharp" /></template>
<style>
.dmvrygbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5h5m-5 4.5h5m-5 4.5h3m5.9-7h1.6l.66-.61l2.43-2.28L17 6v12l-.66-.61l-2.43-2.28l-.66-.61h-2.5v-5zm8.1-.25L22.354 12l-2.604 2.75");
}

</style>
