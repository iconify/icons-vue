<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imm__jb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:teeth-cleaning" /></template>
<style>
.imm__jb1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6c1.5 0 2 1 3 1s1.5-1 3-1c2.25 0 3.5 2 3.5 4.5c0 3-1.25 4.25-1.75 6.5L13 20.5c-.25 1-1.25 1.25-1.75.25L10 17.5c-.5-1-1.5-1-2 0l-1.25 3.25c-.5 1-1.5.75-1.75-.25L4.25 17c-.5-2.25-1.75-3.5-1.75-6.5C2.5 8 3.75 6 6 6Zm13-4q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

</style>
