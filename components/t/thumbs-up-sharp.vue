<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v56corbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thumbs-up-sharp" /></template>
<style>
.v56corbyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.25 10.25l3.5-6.5a2 2 0 0 1 3 2.2l-.9 3.55h4.65l2.75.006l-.55 2.694l-1.4 6.5l-.367 1.796l-1.833.004H8.25Zm-5.5 0h3V20.5h-3z");
}

</style>
