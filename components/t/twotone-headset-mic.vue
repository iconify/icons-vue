<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj8ldb2v"/><path class="tbswislzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-headset-mic" /></template>
<style>
.hgj8ldb2v {
  fill: currentColor;
  d: path("M5 17c0 .55.45 1 1 1h1v-4H5zm12-3h2v4h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tbswislzu {
  fill: currentColor;
  d: path("M12 1a9 9 0 0 0-9 9v7c0 1.66 1.34 3 3 3h3v-8H5v-2c0-3.87 3.13-7 7-7s7 3.13 7 7v2h-4v8h4v1h-7v2h6c1.66 0 3-1.34 3-3V10a9 9 0 0 0-9-9M7 14v4H6c-.55 0-1-.45-1-1v-3zm12 4h-2v-4h2z");
}

</style>
