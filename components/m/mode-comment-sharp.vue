<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an3a52lgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mode-comment-sharp" /></template>
<style>
.an3a52lgo {
  fill: currentColor;
  d: path("M3 17V3h18v17.077L17.923 17z");
}

</style>
