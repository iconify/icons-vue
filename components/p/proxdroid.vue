<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mw_pt9whi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proxdroid" /></template>
<style>
.mw_pt9whi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 8.796za8.26 8.26 0 0 0-11.673.522L24 17.878l-7.827-8.56A8.26 8.26 0 0 0 4.5 8.796L18.402 24L4.5 39.205a8.26 8.26 0 0 0 11.673-.523L24 30.122l7.827 8.56a8.26 8.26 0 0 0 11.673.523L29.598 24Z");
}

</style>
