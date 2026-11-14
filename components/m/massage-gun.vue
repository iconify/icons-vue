<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx7vqzv7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:massage-gun" /></template>
<style>
.gx7vqzv7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.5h9.5a1.25 1.25 0 0 1 1.25 1.25v4A1.25 1.25 0 0 1 13.25 11h-9.5A1.25 1.25 0 0 1 2.5 9.75v-4A1.25 1.25 0 0 1 3.75 4.5ZM7.5 11v8.5a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V11m2-3.25H17m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
