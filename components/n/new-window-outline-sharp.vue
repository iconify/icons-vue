<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npnnymbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:new-window-outline-sharp" /></template>
<style>
.npnnymbeu {
  fill: currentColor;
  d: path("M4 20V4h6.616v1H5v14h14v-5.615h1V20zm12-9V8h-3V7h3V4h1v3h3v1h-3v3z");
}

</style>
