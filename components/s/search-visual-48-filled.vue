<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9rs-mbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-visual-48-filled" /></template>
<style>
.c9rs-mbyq {
  fill: currentColor;
  d: path("M7.5 28A1.5 1.5 0 0 1 9 29.5v6a3.5 3.5 0 0 0 3.5 3.5h6a1.5 1.5 0 0 1 0 3h-6A6.5 6.5 0 0 1 6 35.5v-6A1.5 1.5 0 0 1 7.5 28m33 0a1.5 1.5 0 0 1 1.5 1.5v6a6.5 6.5 0 0 1-6.5 6.5h-6a1.5 1.5 0 0 1 0-3h6a3.5 3.5 0 0 0 3.5-3.5v-6a1.5 1.5 0 0 1 1.5-1.5M24 18a6 6 0 1 1 0 12a6 6 0 0 1 0-12m0 3a3 3 0 1 0 0 6a3 3 0 0 0 0-6M18.5 6a1.5 1.5 0 0 1 0 3h-6A3.5 3.5 0 0 0 9 12.5v6a1.5 1.5 0 0 1-3 0v-6A6.5 6.5 0 0 1 12.5 6zm17 0a6.5 6.5 0 0 1 6.5 6.5v6a1.5 1.5 0 0 1-3 0v-6A3.5 3.5 0 0 0 35.5 9h-6a1.5 1.5 0 0 1 0-3zM15 12.75a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 0 1 0-4.5");
}

</style>
