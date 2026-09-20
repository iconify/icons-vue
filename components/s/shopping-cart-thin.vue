<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gyxdljbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shopping-cart-thin" /></template>
<style>
.gyxdljbdl {
  fill: currentColor;
  d: path("M227.07 61.44A4 4 0 0 0 224 60H59.34l-6.68-36.72A4 4 0 0 0 48.73 20H24a4 4 0 0 0 0 8h21.39l6.69 36.8l19.41 106.78A20 20 0 0 0 79 183.85a24 24 0 1 0 30.87 4.15h60.26a24 24 0 1 0 17.87-8H91.17a12 12 0 0 1-11.8-9.85l-4-22.15H196.1a20 20 0 0 0 19.68-16.42l12.16-66.86a4 4 0 0 0-.87-3.28M108 204a16 16 0 1 1-16-16a16 16 0 0 1 16 16m96 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16m3.91-73.85A12 12 0 0 1 196.1 140H73.88L60.79 68h158.42Z");
}

</style>
