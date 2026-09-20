<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srddibcyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-75-sharp" /></template>
<style>
.srddibcyb {
  fill: currentColor;
  d: path("M6 16.5v-1h1v1zm8 0v-1h4v-3h-4v-5h5v1h-4v3h4v5zm-4.73 0l2-8H7.307v-1h5v.916l-2 8.084z");
}

</style>
