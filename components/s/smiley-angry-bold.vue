<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ja05k7b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:smiley-angry-bold" /></template>
<style>
.ja05k7b-s {
  fill: currentColor;
  d: path("M92 156a16 16 0 1 1 16-16a16 16 0 0 1-16 16m72-32a16 16 0 1 0 16 16a16 16 0 0 0-16-16m72 4A108 108 0 1 1 128 20a108.12 108.12 0 0 1 108 108m-24 0a84 84 0 1 0-84 84a84.09 84.09 0 0 0 84-84M85.34 102l36 24a12 12 0 0 0 13.32 0l36-24a12 12 0 0 0-13.32-20L128 101.58L98.66 82a12 12 0 0 0-13.32 20M154 167.12a51.1 51.1 0 0 0-52 0a12 12 0 1 0 12 20.76a27.13 27.13 0 0 1 28 0a12 12 0 1 0 12-20.76");
}

</style>
