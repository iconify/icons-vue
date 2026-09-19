<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obf8cbbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:playlist-play" /></template>
<style>
.obf8cbbsy {
  fill: currentColor;
  d: path("M3 10h11v2H3zm0-4h11v2H3zm0 8h7v2H3zm13-1v8l6-4z");
}

</style>
