<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stc9vcbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:palpitations" /></template>
<style>
.stc9vcbtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17.25s-5.5-3.5-5.5-7c0-1.75 1.25-3 2.75-3c1.25 0 2.25.75 2.75 1.5c.5-.75 1.5-1.5 2.75-1.5c1.5 0 2.75 1.25 2.75 3c0 3.5-5.5 7-5.5 7ZM3.75 8a9 9 0 0 0 0 8m16.5-8c1.25 2.5 1.25 5.5 0 8");
}

</style>
