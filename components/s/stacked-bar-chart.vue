<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3--6vbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-bar-chart" /></template>
<style>
.h3--6vbwq {
  fill: currentColor;
  d: path("M4 20V9h4v11zM4 8V4h4v4zm6 12v-8h4v8zm0-9V7h4v4zm6 9v-5h4v5zm0-6v-4h4v4z");
}

</style>
