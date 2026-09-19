<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8isohbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pivot-table-chart" /></template>
<style>
.q8isohbmi {
  fill: currentColor;
  d: path("M10 3h11v5H10zm-7 7h5v11H3zm0-7h5v5H3zm15 6l-4 4h3v4h-4v-3l-4 4l4 4v-3h6v-6h3z");
}

</style>
