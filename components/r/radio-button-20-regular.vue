<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g7zz_f2xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:radio-button-20-regular" /></template>
<style>
.g7zz_f2xs {
  fill: currentColor;
  d: path("M10 3a7 7 0 1 0 0 14a7 7 0 0 0 0-14m-8 7a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

</style>
