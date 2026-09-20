<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":101};
const content = `<defs><linearGradient x1="100.93%" y1="181.283%" x2="41.769%" y2="100%" id="ssvg-id-zeita"><stop offset="0%" class="tlcmntu3e"/><stop offset="100%"/></linearGradient></defs><path fill="url(#ssvg-id-zeita)" class="szw45x06q"/><path class="wy4ifzlxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:zeit" /></template>
<style>
.szw45x06q {
  d: path("M56.858 0l56.857 100.875H0z");
}

.tlcmntu3e {
  stop-color: var(--svg-color--fff, #FFF);
}

.wy4ifzlxp {
  d: path("M191.26 75.835h45.613v-7.918h-34.237l33.68-48.066v-6.914h-44.498v7.918h33.122L191.26 68.92v6.914zm93.345 0h40.928v-7.918h-31.672V47.731h27.546v-7.918H293.86V20.855h31.672v-7.918h-40.928v62.898zm90.221 0h39.925v-7.918h-15.279V20.855h15.279v-7.918h-39.925v7.918h15.39v47.062h-15.39v7.918zm105.611 0h9.257v-54.98h21.412v-7.918h-51.858v7.918h21.19v54.98z");
  fill: var(--svg-color--333, #333);
}

</style>
