<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wv6zeab3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:row-triple-20-filled" /></template>
<style>
.wv6zeab3n {
  fill: currentColor;
  d: path("M4.5 2A1.5 1.5 0 0 0 3 3.5v1A1.5 1.5 0 0 0 4.5 6h11A1.5 1.5 0 0 0 17 4.5v-1A1.5 1.5 0 0 0 15.5 2zm0 6A1.5 1.5 0 0 0 3 9.5v1A1.5 1.5 0 0 0 4.5 12h11a1.5 1.5 0 0 0 1.5-1.5v-1A1.5 1.5 0 0 0 15.5 8zm0 6A1.5 1.5 0 0 0 3 15.5v1A1.5 1.5 0 0 0 4.5 18h11a1.5 1.5 0 0 0 1.5-1.5v-1a1.5 1.5 0 0 0-1.5-1.5z");
}

</style>
