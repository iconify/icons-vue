<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wvwr8jupi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wifi-4-20-filled" /></template>
<style>
.wvwr8jupi {
  fill: currentColor;
  d: path("M10.922 13.881a1.242 1.242 0 1 1-1.757 1.757a1.242 1.242 0 0 1 1.757-1.757");
}

</style>
