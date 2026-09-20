<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ggz9b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-sharp" /></template>
<style>
.y4ggz9b8w {
  fill: currentColor;
  d: path("M2 20V4h20v16zm11-10h7V6h-7z");
}

</style>
