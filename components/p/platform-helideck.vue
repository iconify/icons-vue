<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbh5ckkhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:platform-helideck" /></template>
<style>
.kbh5ckkhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.731 2.992l5.277 5.277v7.462l-5.277 5.277H8.269l-5.277-5.277V8.269l5.277-5.277ZM9 7.5v9m6-9v9M9 12h6");
}

</style>
