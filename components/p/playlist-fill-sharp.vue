<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhdsrebzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-fill-sharp" /></template>
<style>
.rhdsrebzt {
  fill: currentColor;
  d: path("M3 5h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m11 5a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 14 18ZM3 11h8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m13 5.131L19.197 14L16 11.869ZM3 17h8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
