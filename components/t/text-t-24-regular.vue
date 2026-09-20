<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5q8hdbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-t-24-regular" /></template>
<style>
.v5q8hdbdl {
  fill: currentColor;
  d: path("M5 4.75A.75.75 0 0 1 5.75 4h12.5a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0V5.5h-4.75v13h1.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-13H6.5v1.25a.75.75 0 0 1-1.5 0z");
}

</style>
