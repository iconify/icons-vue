<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ofb_8gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:warehouse-sharp" /></template>
<style>
.j8ofb_8gd {
  fill: currentColor;
  d: path("M2 21V7l10-4l10 4v14h-6v-8H8v8zm7 0v-2h2v2zm2-3v-2h2v2zm2 3v-2h2v2z");
}

</style>
