<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joc2qfslj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:pages" /></template>
<style>
.joc2qfslj {
  fill: currentColor;
  d: path("M3 5v6h5L7 7l4 1V3H5c-1.1 0-2 .9-2 2m5 8H3v6c0 1.1.9 2 2 2h6v-5l-4 1zm9 4l-4-1v5h6c1.1 0 2-.9 2-2v-6h-5zm2-14h-6v5l4-1l-1 4h5V5c0-1.1-.9-2-2-2");
}

</style>
