<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iagij1b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-new-page-20-filled" /></template>
<style>
.iagij1b6k {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3H8v2.5A1.5 1.5 0 0 0 9.5 7H17v7.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5zM8 11a1 1 0 1 0-2 0a1 1 0 0 0 2 0m2 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2m4-1a1 1 0 1 0-2 0a1 1 0 0 0 2 0m3-5v-.5A2.5 2.5 0 0 0 14.5 3H9v2.5a.5.5 0 0 0 .5.5z");
}

</style>
