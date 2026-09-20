<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7n1b4iis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reorder-outline-sharp" /></template>
<style>
.c7n1b4iis {
  fill: currentColor;
  d: path("M3 19v-2h18v2zm0-4v-2h18v2zm0-4V9h18v2zm0-4V5h18v2z");
}

</style>
