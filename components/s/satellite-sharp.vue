<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfr3dvlmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:satellite-sharp" /></template>
<style>
.dfr3dvlmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.71 8.71l2.58 2.58l.71.71l-.71.71l-2.58 2.58L12 16l-.71-.71l-2.58-2.58L8 12l.71-.71l2.58-2.58L12 8zM8.44 3.14l1.42 1.42l.53.53l-.53.53l-4.24 4.24l-.53.53l-.53-.53l-1.42-1.42l-.53-.53l.53-.53l4.24-4.24l.53-.53zm11 11l1.42 1.42l.53.53l-.53.53l-4.24 4.24l-.53.53l-.53-.53l-1.42-1.42l-.53-.53l.53-.53l4.24-4.24l.53-.53zM10 10L7.75 7.75M14 14l2.25 2.25m-11-11l2.5 2.5m8.5 8.5l2.5 2.5m-9.09-1.23a6 6 0 0 1-3.18-3.18m2 5.94a9 9 0 0 1-4.76-4.76");
}

</style>
