<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfzn0xbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:navigation-outline" /></template>
<style>
.pfzn0xbgq {
  fill: currentColor;
  d: path("m5 21l-1-1l8-18l8 18l-1 1l-7-3zm2.1-3.1l4.9-2.1l4.9 2.1l-4.9-11zm4.9-2.1");
}

</style>
