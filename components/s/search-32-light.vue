<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x5ajqhdwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-32-light" /></template>
<style>
.x5ajqhdwh {
  fill: currentColor;
  d: path("M6.368 6.368c4.491-4.49 11.773-4.49 16.264 0c4.372 4.373 4.486 11.39.344 15.902l6.876 6.877a.5.5 0 0 1-.707.707l-6.876-6.877c-4.512 4.14-11.528 4.027-15.9-.345c-4.492-4.491-4.492-11.773 0-16.264m15.557.707c-4.1-4.1-10.75-4.1-14.85 0s-4.1 10.75 0 14.85s10.75 4.1 14.85 0s4.1-10.75 0-14.85");
}

</style>
