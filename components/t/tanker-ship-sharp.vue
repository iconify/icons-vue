<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is-0fyyhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tanker-ship-sharp" /></template>
<style>
.is-0fyyhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5a3 3 0 0 1 6 0Zm6.75 0a3 3 0 0 1 6 0Zm7 0V5.75H21v6.75Zm-14.75 0h18.5l-1.75 3.9l-.439 1.097l-1.181.003H6.12l-1.181-.003L4.5 16.4Zm0 8.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>
