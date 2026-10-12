<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzbq4rbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-lander-sharp" /></template>
<style>
.kzbq4rbjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3.5h6l.51.86l1.98 3.28l.51.86l-.51.86l-1.98 3.28l-.51.86h-7l-.51-.86l-1.98-3.28l-.51-.86l.51-.86l1.98-3.28l.51-.86zm-1 10L5 20.75m7-7.25v7.25m3.5-7.25l3.5 7.25");
}

</style>
