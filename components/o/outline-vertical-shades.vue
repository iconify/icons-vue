<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyyeshb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-vertical-shades" /></template>
<style>
.uyyeshb6v {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM14 5v14h-4V5zM6 5h2v14H6zm10 14V5h2v14z");
}

</style>
