<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqe799quy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-call" /></template>
<style>
.pqe799quy {
  fill: currentColor;
  d: path("M17 10.5V6H3v12h14v-4.5l4 4v-11zM14 13h-3v3H9v-3H6v-2h3V8h2v3h3z");
}

</style>
