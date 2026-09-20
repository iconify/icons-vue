<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dm-61tbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shuffle-simple-light" /></template>
<style>
.dm-61tbml {
  fill: currentColor;
  d: path("M214 48v40a6 6 0 0 1-12 0V62.48l-47.13 47.14a6 6 0 0 1-8.49-8.49L193.52 54H168a6 6 0 0 1 0-12h40a6 6 0 0 1 6 6m-6 114a6 6 0 0 0-6 6v25.52L52.24 43.76a6 6 0 0 0-8.48 8.48L193.52 202H168a6 6 0 0 0 0 12h40a6 6 0 0 0 6-6v-40a6 6 0 0 0-6-6m-106.87-15.62l-57.37 57.38a6 6 0 1 0 8.48 8.48l57.38-57.37a6 6 0 0 0-8.49-8.49");
}

</style>
