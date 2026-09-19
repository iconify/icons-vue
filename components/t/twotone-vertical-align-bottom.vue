<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu2qubb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-vertical-align-bottom" /></template>
<style>
.wu2qubb-z {
  fill: currentColor;
  d: path("M11 3v10H8l4 4l4-4h-3V3zM4 19h16v2H4z");
}

</style>
