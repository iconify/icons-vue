<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vwfzrzb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:page-fit-16-filled" /></template>
<style>
.vwfzrzb-b {
  fill: currentColor;
  d: path("M1 5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2zm2 1v1a.5.5 0 0 0 1 0V6h1a.5.5 0 0 0 0-1H4a1 1 0 0 0-1 1m9-1h-1a.5.5 0 0 0 0 1h1v1a.5.5 0 0 0 1 0V6a1 1 0 0 0-1-1m0 6a1 1 0 0 0 1-1V9a.5.5 0 0 0-1 0v1h-1a.5.5 0 0 0 0 1zm-8 0h1a.5.5 0 0 0 0-1H4V9a.5.5 0 0 0-1 0v1a1 1 0 0 0 1 1");
}

</style>
