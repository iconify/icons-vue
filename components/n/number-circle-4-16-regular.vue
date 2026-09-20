<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hapc-tbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-4-16-regular" /></template>
<style>
.hapc-tbwz {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-7a7 7 0 1 0 0 14A7 7 0 0 0 8 1m1 4.378c0-.755-.99-1.037-1.387-.396L5.07 9.084a.6.6 0 0 0 .51.916H8v1a.5.5 0 0 0 1 0v-1h.5a.5.5 0 0 0 0-1H9zm-1 .877V9H6.3z");
}

</style>
