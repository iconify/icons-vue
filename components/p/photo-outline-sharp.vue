<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2pb0y17x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-outline-sharp" /></template>
<style>
.y2pb0y17x {
  fill: currentColor;
  d: path("M6 17h12l-3.75-5l-3 4L9 13zm-3 4V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
