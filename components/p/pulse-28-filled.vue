<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wz2gizk3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pulse-28-filled" /></template>
<style>
.wz2gizk3t {
  fill: currentColor;
  d: path("M10.035 3a1 1 0 0 1 .94.78l3.712 16.496l3.864-11.592a1 1 0 0 1 1.878-.055L22.177 13H25a1 1 0 1 1 0 2h-3.5a1 1 0 0 1-.928-.629l-.987-2.465l-4.136 12.41a1 1 0 0 1-1.925-.096L9.862 7.94l-1.904 6.347A1 1 0 0 1 7 15H3a1 1 0 1 1 0-2h3.256l2.786-9.287A1 1 0 0 1 10.035 3");
}

</style>
