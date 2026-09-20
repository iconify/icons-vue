<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n2fc5ebyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:molecule-32-regular" /></template>
<style>
.n2fc5ebyy {
  fill: currentColor;
  d: path("M22 16a7 7 0 1 0-6.406-4.174l-2.83 2.2a5.5 5.5 0 1 0-.269 7.252l4.776 2.68a4.5 4.5 0 1 0 1.09-1.682l-4.775-2.679A5.5 5.5 0 0 0 14 17.5c0-.59-.093-1.16-.266-1.694l2.929-2.277A6.99 6.99 0 0 0 22 16m0-2a5 5 0 1 1 0-10a5 5 0 0 1 0 10M8.5 21a3.5 3.5 0 1 1 0-7a3.5 3.5 0 0 1 0 7M24 25.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0");
}

</style>
