<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgferhblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-phillips-outline" /></template>
<style>
.hgferhblh {
  fill: currentColor;
  d: path("M7 21v-2h10v2zm0-3V8l3.75-5h2.5L17 8v10zm2-2h6v-2.175l-3-3l-3 3zm0-5l2-2V6L9 8.675zm6 0V8.675L13 6v3zm0 5H9z");
}

</style>
