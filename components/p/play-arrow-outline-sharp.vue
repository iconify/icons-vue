<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgaoxullz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-arrow-outline-sharp" /></template>
<style>
.pgaoxullz {
  fill: currentColor;
  d: path("M9 17.192V6.808L17.154 12zm1-1.842L15.289 12L10 8.65z");
}

</style>
