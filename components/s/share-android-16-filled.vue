<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fcqkg0b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-android-16-filled" /></template>
<style>
.fcqkg0b2r {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 1 .492 1.313L5.956 7.581a2 2 0 0 1 0 .838l4.536 2.268a2 2 0 1 1-.447.894L5.507 9.313a2 2 0 1 1 0-2.626l4.536-2.268A2 2 0 0 1 10 4");
}

</style>
