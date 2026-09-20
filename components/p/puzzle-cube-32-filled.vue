<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysiu7-bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-cube-32-filled" /></template>
<style>
.ysiu7-bth {
  fill: currentColor;
  d: path("M10 22v6.987l.001.013H7.5A4.5 4.5 0 0 1 3 24.5V22zm10 0v7h-8.001l.001-.013V22zm9 0v2.5a4.5 4.5 0 0 1-4.5 4.5H22v-7zM10 12v8H3v-8zm10 0v8h-8v-8zm9 0v8h-7v-8zm-9-9v7h-8V3zm4.5 0A4.5 4.5 0 0 1 29 7.5V10h-7V3z");
}

</style>
