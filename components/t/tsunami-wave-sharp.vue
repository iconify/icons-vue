<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2mtuzbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tsunami-wave-sharp" /></template>
<style>
.h2mtuzbds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V11c0-4.5 3.75-8.25 8.5-8.25c3.75 0 6.5 2.5 6.5 5.5c0 2-1.5 3.5-3.5 3.5h-2.5V8.5l.75-.75c-3 .25-5 3-5 6.25v7.25Zm9.75-.6v-3.9l.48-.36l3.29-2.53l.48-.36l.48.36l3.29 2.53l.48.36v4.5h-8.5z");
}

</style>
