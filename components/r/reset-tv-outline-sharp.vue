<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-nyacbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reset-tv-outline-sharp" /></template>
<style>
.x-nyacbyq {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v5h-2V5H4v12h16v-5h-7.2l1.85 1.85l-1.4 1.4L9 11l4.25-4.25l1.4 1.4L12.8 10H22v9h-6v2zm5-10");
}

</style>
