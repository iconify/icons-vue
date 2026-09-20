<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqa2-b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tile-large-outline" /></template>
<style>
.iuqa2-b-s {
  fill: currentColor;
  d: path("M4 20v-4.942h6.789V20zm9.173 0v-4.942H20V20zM5 19h4.789v-2.942H5zm9.173 0H19v-2.942h-4.827zM4 12.673V4h16v8.673zm12.596 4.846");
}

</style>
