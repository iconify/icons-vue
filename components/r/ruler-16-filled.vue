<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nfgqqj3ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ruler-16-filled" /></template>
<style>
.nfgqqj3ms {
  fill: currentColor;
  d: path("M10.5 1A1.5 1.5 0 0 1 12 2.5v11a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 4 13.5v-11A1.5 1.5 0 0 1 5.5 1zM5 12.5h3.5a.5.5 0 0 0 0-1H5zM5 10h2.5a.5.5 0 0 0 0-1H5zm0-2.5h3.5a.5.5 0 0 0 0-1H5zM5 5h2.5a.5.5 0 0 0 0-1H5z");
}

</style>
