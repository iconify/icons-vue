<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aftyltbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-filter-sharp" /></template>
<style>
.aftyltbbj {
  fill: currentColor;
  d: path("m9.5 11l-.95 2.05L6.5 14l2.05.95L9.5 17l.95-2.05L12.5 14l-2.05-.95L9.5 11Zm6 0l-.65 1.35l-1.35.65l1.35.65l.65 1.35l.65-1.35L17.5 13l-1.35-.65L15.5 11ZM2 20V4h2l2 4h3L7 4h2l2 4h3l-2-4h2l2 4h3l-2-4h5v16H2Z");
}

</style>
