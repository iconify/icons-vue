<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-8w25b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-poles-crossed" /></template>
<style>
.x-8w25b3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 20.5l11-14m2 14l-11-14m10.203-4.447L20.067 3.9l-2.77 3.547L14.933 5.6ZM3.933 3.9l2.364-1.847L9.067 5.6L6.703 7.447ZM5.5 17.25l3 2.5m10-2.5l-3 2.5");
}

</style>
