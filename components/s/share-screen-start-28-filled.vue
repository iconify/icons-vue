<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="orpb45i7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-start-28-filled" /></template>
<style>
.orpb45i7l {
  fill: currentColor;
  d: path("M4.25 4.999A2.25 2.25 0 0 0 2 7.249v13.5A2.25 2.25 0 0 0 4.25 23h19.5A2.25 2.25 0 0 0 26 20.75V7.25A2.25 2.25 0 0 0 23.75 5zM14.528 8.84l3.255 3.255a.75.75 0 0 1-1.061 1.06l-1.974-1.974v7.447a.75.75 0 0 1-1.5 0v-7.445l-1.97 1.972a.75.75 0 1 1-1.061-1.06l3.25-3.254a.75.75 0 0 1 1.061 0");
}

</style>
