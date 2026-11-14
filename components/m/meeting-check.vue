<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqwwkjzjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meeting-check" /></template>
<style>
.uqwwkjzjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Zm-2.645 2.24a7.25 7.25 0 0 1 0-4.48m13.898.364a7.25 7.25 0 0 1 0 3.752m-6.45 5.353q-.708.054-1.413-.03q-.705-.085-1.38-.304m.364-13.898a7.25 7.25 0 0 1 3.752 0M14.75 18l2 2L21 15.75");
}

</style>
