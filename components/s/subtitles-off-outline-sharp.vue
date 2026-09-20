<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n12jqcnfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subtitles-off-outline-sharp" /></template>
<style>
.n12jqcnfy {
  fill: currentColor;
  d: path("M2 20V4h2l2 2H4v12h11.15l-2-2H6v-2h5.15L.65 3.45l1.4-1.4l19.9 19.9l-1.4 1.4l-3.4-3.35zm18-2.85V6H8.85l-2-2H22v15.15zM14.85 12l-2-2H18v2zM6 12v-2h2v2zm3.575.425");
}

</style>
