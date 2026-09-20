<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0ynxsbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:photo-filter-24-regular" /></template>
<style>
.n0ynxsbxb {
  fill: currentColor;
  d: path("M9.5 2a7.5 7.5 0 0 1 7.179 5.321a7.5 7.5 0 1 1-9.357 9.358A7.5 7.5 0 0 1 9.5 2m7.486 7.038l.01.22L17 9.5a7.5 7.5 0 0 1-7.962 7.486a6 6 0 1 0 7.947-7.948M9.5 3.5a6 6 0 0 0-2.486 11.463l-.01-.22L7 14.5a7.5 7.5 0 0 1 7.962-7.486A6 6 0 0 0 9.5 3.5");
}

</style>
