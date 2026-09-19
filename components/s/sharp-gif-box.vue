<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh5k1f0eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-gif-box" /></template>
<style>
.hh5k1f0eu {
  fill: currentColor;
  d: path("M21 3H3v18h18zM9.5 13v-1h1v2h-3v-4h3v1h-2v2zm3 1h-1v-4h1zm4-3h-2v.5H16v1h-1.5V14h-1v-4h3z");
}

</style>
