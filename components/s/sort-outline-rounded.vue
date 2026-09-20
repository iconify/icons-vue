<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbadfab2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sort-outline-rounded" /></template>
<style>
.sbadfab2z {
  fill: currentColor;
  d: path("M4 18q-.425 0-.712-.288T3 17t.288-.712T4 16h4q.425 0 .713.288T9 17t-.288.713T8 18zm0-5q-.425 0-.712-.288T3 12t.288-.712T4 11h10q.425 0 .713.288T15 12t-.288.713T14 13zm0-5q-.425 0-.712-.288T3 7t.288-.712T4 6h16q.425 0 .713.288T21 7t-.288.713T20 8z");
}

</style>
