<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pynkkonnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-in-ar" /></template>
<style>
.pynkkonnz {
  fill: currentColor;
  d: path("M18 1v2h3v3h2V1zm3 20h-3v2h5v-5h-2zM3 3h3V1H1v5h2zm0 15H1v5h5v-2H3zM19 7.97l-7-4.03l-7 4.03v8.06l7 4.03l7-4.03zm-8 9.2l-4-2.3v-4.63l4 2.33zm1-6.33L8.04 8.53L12 6.25l3.96 2.28zm5 4.03l-4 2.3v-4.6l4-2.33z");
}

</style>
