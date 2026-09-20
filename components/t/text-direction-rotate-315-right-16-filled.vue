<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qirf1e17d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-315-right-16-filled" /></template>
<style>
.qirf1e17d {
  fill: currentColor;
  d: path("M14.252 6a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-.69L7.28 14.78a.75.75 0 0 1-1.06-1.06l6.22-6.22h-.69a.75.75 0 0 1 0-1.5zM1.22 5.22a.75.75 0 0 1 .818-.161l6 2.499a.751.751 0 0 1-.577 1.385l-1.216-.507l-1.81 1.81l.507 1.216a.75.75 0 0 1-1.384.576l-2.5-5.999a.75.75 0 0 1 .162-.818M3.81 8.75l.938-.937l-1.606-.67zM9.252 1a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-.691L6.78 5.28a.75.75 0 0 1-1.06-1.06L7.44 2.5h-.688a.75.75 0 1 1 0-1.5z");
}

</style>
