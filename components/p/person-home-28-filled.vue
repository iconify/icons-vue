<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="fafvh1b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-28-filled" /></template>
<style>
.fafvh1b7b {
  fill: currentColor;
  d: path("M19.2 14.48a2 2 0 0 1 2.6 0l4.5 3.856a2 2 0 0 1 .7 1.519v5.647a1.5 1.5 0 0 1-1.5 1.5H24a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 0-1.5-1.5h-1a1.5 1.5 0 0 0-1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5v-5.647a2 2 0 0 1 .7-1.52zm-5.152 3.096A3 3 0 0 0 13 19.855V25.5q.001.243.046.474C7.754 25.708 4 23.225 4 19.715V19a3 3 0 0 1 3-3h8.888zM14 2a6 6 0 1 1 0 12a6 6 0 0 1 0-12");
}

</style>
