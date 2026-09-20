<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v1n64tpfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pill" /></template>
<style>
.v1n64tpfe {
  fill: currentColor;
  d: path("M216.42 39.6a53.26 53.26 0 0 0-75.32 0L39.6 141.09a53.26 53.26 0 0 0 75.32 75.31l101.51-101.49a53.31 53.31 0 0 0-.01-75.31M103.61 205.09a37.26 37.26 0 0 1-52.7-52.69L96 107.31L148.7 160Zm101.5-101.49L160 148.69L107.32 96l45.1-45.09a37.26 37.26 0 0 1 52.69 52.69m-15.43-21.26a8 8 0 0 1 0 11.32l-24 24a8 8 0 1 1-11.31-11.32l24-24a8 8 0 0 1 11.31 0");
}

</style>
