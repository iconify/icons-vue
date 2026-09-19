<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw62h6bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-price-check" /></template>
<style>
.mw62h6bhq {
  fill: currentColor;
  d: path("M11 13V9c0-.55-.45-1-1-1H6V6h5V4H8.5V3h-2v1H5c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1h4v2H4v2h2.5v1h2v-1H10c.55 0 1-.45 1-1m8.59-.48l-5.66 5.65l-2.83-2.83l-1.41 1.42L13.93 21L21 13.93z");
}

</style>
