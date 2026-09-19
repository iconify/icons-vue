<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws7vmacpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:view-array" /></template>
<style>
.ws7vmacpo {
  fill: currentColor;
  d: path("M21 5h-3v14h3zm-4 0H7v14h10zM6 5H3v14h3z");
}

</style>
