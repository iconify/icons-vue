<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr4jem6sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-assistant-direction" /></template>
<style>
.dr4jem6sl {
  fill: currentColor;
  d: path("M13.5 10H8v5h2v-3h3.5v2.5L17 11l-3.5-3.5zM12 1C5.9 1 1 5.9 1 12s4.9 11 11 11s11-4.9 11-11S18.1 1 12 1m8.31 11l-8.34 8.37L3.62 12l8.34-8.37z");
}

</style>
