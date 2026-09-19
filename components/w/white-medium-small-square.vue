<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m6-lu3s9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:white-medium-small-square" /></template>
<style>
.m6-lu3s9q {
  fill: currentColor;
  d: path("M50 14v36H14V14zm2-2H12v40h40z");
}

</style>
