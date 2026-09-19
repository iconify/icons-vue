<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag3gqy5at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-playlist-remove" /></template>
<style>
.ag3gqy5at {
  fill: currentColor;
  d: path("M13.71 21.3c.39.39 1.02.39 1.41 0L17 19.41l1.89 1.89a.996.996 0 1 0 1.41-1.41L18.41 18l1.89-1.89a.996.996 0 1 0-1.41-1.41L17 16.59l-1.89-1.89a.996.996 0 1 0-1.41 1.41L15.59 18l-1.89 1.89c-.38.38-.38 1.02.01 1.41M14 11c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1s.45 1 1 1h9c.55 0 1-.45 1-1m0-4c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1s.45 1 1 1h9c.55 0 1-.45 1-1M3 15c0 .55.45 1 1 1h5c.55 0 1-.45 1-1s-.45-1-1-1H4c-.55 0-1 .45-1 1");
}

</style>
