<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dphqtabvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-upgrade" /></template>
<style>
.dphqtabvo {
  fill: currentColor;
  d: path("M16 19c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1s.45-1 1-1h6c.55 0 1 .45 1 1M11 7.99V15c0 .55.45 1 1 1s1-.45 1-1V7.99h1.79c.45 0 .67-.54.35-.85l-2.79-2.78a.513.513 0 0 0-.71 0L8.86 7.14c-.32.31-.1.85.35.85z");
}

</style>
