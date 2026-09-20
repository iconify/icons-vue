<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="atn4hjwjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtract-square-thin" /></template>
<style>
.atn4hjwjl {
  fill: currentColor;
  d: path("M216 92h-52V40a4 4 0 0 0-4-4H40a4 4 0 0 0-4 4v120a4 4 0 0 0 4 4h52v52a4 4 0 0 0 4 4h120a4 4 0 0 0 4-4V96a4 4 0 0 0-4-4m-54.34 120l-48-48h44.68l48 48Zm2.34-53.66v-44.68l48 48v44.68ZM212 100v50.34l-48-48V100ZM44 44h112v112H44Zm56 120h2.34l48 48H100Z");
}

</style>
