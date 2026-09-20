<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6kemcbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-16-filled" /></template>
<style>
.y6kemcbim {
  fill: currentColor;
  d: path("M7.5 9a2 2 0 0 1 2 2c0 .965-.592 1.73-1.411 2.23C7.27 13.728 6.175 14 5 14s-2.27-.272-3.089-.77C1.091 12.73.5 11.965.5 11a2 2 0 0 1 2-2zm6.653.008A1.5 1.5 0 0 1 15.5 10.5c0 .771-.47 1.409-1.102 1.83c-.635.424-1.485.67-2.398.67c-.7 0-1.36-.146-1.917-.403c.258-.463.416-.996.416-1.597c0-.759-.284-1.45-.749-1.979q.122-.02.25-.021h4zM5 2.5A2.75 2.75 0 1 1 5 8a2.75 2.75 0 0 1 0-5.5m7.002.997a2.252 2.252 0 1 1 0 4.503a2.252 2.252 0 0 1 0-4.503");
}

</style>
