<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afg8anjae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-arrow-outline-sharp" /></template>
<style>
.afg8anjae {
  fill: currentColor;
  d: path("M8 19V5l11 7zm2-3.65L15.25 12L10 8.65z");
}

</style>
