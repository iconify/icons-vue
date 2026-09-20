<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x3avk53-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-20-filled" /></template>
<style>
.x3avk53-e {
  fill: currentColor;
  d: path("M10 2c4.419 0 8 3.586 8 8c0 1.973-.956 3.587-1.97 4.747a12 12 0 0 1-1.926 1.753h3.146a.75.75 0 0 1 0 1.5h-4.03a1.22 1.22 0 0 1-1.215-1.098l-.006-.124l.01-.163a1.25 1.25 0 0 1 .577-.892l.419-.279A10.8 10.8 0 0 0 14.9 13.76c.886-1.013 1.6-2.288 1.6-3.76a6.5 6.5 0 0 0-13 0c0 1.472.713 2.747 1.6 3.76a11 11 0 0 0 2.314 1.963c.355.222.587.615.587 1.055c0 .675-.547 1.222-1.222 1.222H2.75a.75.75 0 0 1 0-1.5h3.146a12 12 0 0 1-1.925-1.753C2.956 13.587 2 11.973 2 10a8 8 0 0 1 8-8");
}

</style>
