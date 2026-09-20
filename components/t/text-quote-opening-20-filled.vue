<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b4wb2bbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-quote-opening-20-filled" /></template>
<style>
.b4wb2bbqq {
  fill: currentColor;
  d: path("M11 13.5a2.5 2.5 0 1 0 1.174-2.12a8.8 8.8 0 0 1 .952-2.764c.649-1.18 1.476-2.011 2.228-2.762a.5.5 0 0 0-.708-.708l-.012.012c-.746.747-1.663 1.664-2.385 2.976C11.52 9.462 11 11.17 11 13.5m-5.826-2.12A2.5 2.5 0 1 1 4 13.5c0-2.33.52-4.038 1.25-5.366c.721-1.312 1.638-2.23 2.385-2.976l.011-.012a.5.5 0 1 1 .708.708c-.752.751-1.579 1.581-2.228 2.762a8.8 8.8 0 0 0-.952 2.765");
}

</style>
