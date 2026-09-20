<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx69kabod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:playlist-play-sharp" /></template>
<style>
.xx69kabod {
  fill: currentColor;
  d: path("M3 16v-2h8v2zm0-4v-2h12v2zm0-4V6h12v2zm13 13v-8l6 4z");
}

</style>
