<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lspz5580a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plexus" /></template>
<style>
.lspz5580a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.474 8.508l35.051 30.984m0-30.984L6.474 39.492M43.5 11.082l-39 25.836m39 0l-39-25.836");
}

</style>
