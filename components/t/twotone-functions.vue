<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd3xp2y2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-functions" /></template>
<style>
.cd3xp2y2d {
  fill: currentColor;
  d: path("M18 17h-7l5-5l-5-5h7V4H6v2l6.5 6L6 18v2h12z");
}

</style>
