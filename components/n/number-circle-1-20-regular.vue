<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ow7tcubhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-1-20-regular" /></template>
<style>
.ow7tcubhy {
  fill: currentColor;
  d: path("M11 6.5a.5.5 0 0 0-.985-.121c-.103.41-.373.911-.727 1.383c-.354.471-.752.863-1.065 1.072a.5.5 0 0 0 .554.832c.405-.27.845-.705 1.223-1.19V13.5a.5.5 0 1 0 1 0zM10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-7 8a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
