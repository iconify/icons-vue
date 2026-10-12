<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwycyz-7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whale-tail-sharp" /></template>
<style>
.nwycyz-7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.25c-1.5-3-4.5-4.5-8.75-4.75C4 11 7 13.5 10.5 13.75l.5 3.75h2l.5-3.75C17 13.5 20 11 20.75 7.5c-4.25.25-7.25 1.75-8.75 4.75Zm-9.25 8.5C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

</style>
