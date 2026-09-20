<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ev2xq7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:variable-add-outline" /></template>
<style>
.k6ev2xq7y {
  fill: currentColor;
  d: path("M14 16H4V8h16v2h-1V9H5v6h9zm-9-1V9zm14 4v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
