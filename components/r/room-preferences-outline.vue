<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvx3ijbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:room-preferences-outline" /></template>
<style>
.wvx3ijbuu {
  fill: currentColor;
  d: path("M4.5 20v-1h2V4h8v1h3v5.808h-1V6h-2v6.462h-1V5h-6v14h4.77v1zm12.77.577l-.109-.866q-.569-.125-.937-.352t-.695-.561l-.796.366l-.577-.86l.702-.577q-.185-.548-.185-1.032q0-.483.185-1.031l-.702-.577l.577-.86l.796.365q.327-.334.695-.564t.938-.355l.107-.865h1l.108.865q.57.125.938.352t.694.562l.797-.366l.577.86l-.702.577q.185.548.185 1.032q0 .483-.185 1.031l.702.577l-.577.86l-.796-.36q-.327.335-.695.562q-.369.227-.938.352l-.108.865zm.5-1.73q.882 0 1.518-.637q.635-.635.635-1.518t-.635-1.518t-1.519-.636t-1.518.636t-.636 1.518t.636 1.518t1.518.636m-6.808-6.306q-.23-.23-.23-.54t.23-.54t.539-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23M7.5 19V5z");
}

</style>
