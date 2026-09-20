<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="irylg4lsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-right-16-regular" /></template>
<style>
.irylg4lsa {
  fill: currentColor;
  d: path("M14 2.5a.5.5 0 0 0-1 0v11a.5.5 0 0 0 1 0zm-12 9A2.5 2.5 0 0 0 4.5 14h5a.5.5 0 0 0 .5-.5v-11a.5.5 0 0 0-.5-.5h-5A2.5 2.5 0 0 0 2 4.5zM9 3v2H6V3zm0 3v4H6V6zm0 5v2H6v-2zm-6-1V6h2v4zm0-5v-.5A1.5 1.5 0 0 1 4.5 3H5v2zm0 6h2v2h-.5A1.5 1.5 0 0 1 3 11.5z");
}

</style>
