<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uxogarz6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shapes-bold" /></template>
<style>
.uxogarz6a {
  fill: currentColor;
  d: path("M71.49 60.55a12 12 0 0 0-23 0l-36 120A12 12 0 0 0 24 196h72a12 12 0 0 0 11.49-15.45ZM40.13 172L60 105.76L79.87 172ZM212 74a54 54 0 1 0-54 54a54.06 54.06 0 0 0 54-54m-84 0a30 30 0 1 1 30 30a30 30 0 0 1-30-30m96 70h-88a12 12 0 0 0-12 12v52a12 12 0 0 0 12 12h88a12 12 0 0 0 12-12v-52a12 12 0 0 0-12-12m-12 52h-64v-28h64Z");
}

</style>
