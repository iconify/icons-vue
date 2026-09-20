<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="zu9vynb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:open-folder-28-filled" /></template>
<style>
.zu9vynb4g {
  fill: currentColor;
  d: path("M3 7.75a5 5 0 0 1 5-5h12a5 5 0 0 1 5 5V13a1 1 0 1 1-2 0V7.75a3 3 0 0 0-3-3H8a3 3 0 0 0-3 3V20a3 3 0 0 0 3 3h5a1 1 0 1 1 0 2H8a5 5 0 0 1-5-5zM10 11a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2h-5.53l8.24 8.295a1 1 0 0 1-1.42 1.41L12 13.358V19a1 1 0 1 1-2 0z");
}

</style>
