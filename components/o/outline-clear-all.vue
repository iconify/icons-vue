<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c--36ycir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-clear-all" /></template>
<style>
.c--36ycir {
  fill: currentColor;
  d: path("M5 13h14v-2H5zm-2 4h14v-2H3zM7 7v2h14V7z");
}

</style>
