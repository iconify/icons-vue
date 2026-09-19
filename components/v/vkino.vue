<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v-3-0_ney"/><path class="swgp9-66g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vkino" /></template>
<style>
.swgp9-66g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.994 19l5 5l-5 5");
}

.v-3-0_ney {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.305 11.368c-.826.054-1.534.772-1.576 1.6a231 231 0 0 0-.222 6.143a4.89 4.89 0 0 1 0 9.778q.07 3.09.222 6.144c.041.827.75 1.545 1.576 1.599c5.734.37 11.691.562 17.688.569c5.998-.007 11.955-.2 17.688-.57c.827-.053 1.535-.77 1.576-1.598q.151-3.055.223-6.146a4.89 4.89 0 0 1 .013-9.776q-.063-3.098-.207-6.163c-.039-.827-.746-1.545-1.572-1.597a281 281 0 0 0-17.721-.552c-5.998.007-11.955.2-17.69.57zM16.994 24h14");
}

</style>
