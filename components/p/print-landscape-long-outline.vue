<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9_8axn6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-landscape-long-outline" /></template>
<style>
.o9_8axn6j {
  fill: currentColor;
  d: path("M4 13h2v4h13V7h2v10q0 .825-.587 1.413T19 19H6q-.825 0-1.412-.587T4 17zm10-9h3v1h2q.85 0 1.425.563T21 7q0 .225-.05.475t-.162.575t-.288.762t-.45 1.038q-.225.525-.538 1.112t-.887 1.813q-.275.55-.775.888T16.775 14H4q-1.125 0-1.725-.913t-.1-1.862q.65-1.35 1.075-2.675t.625-2.05q.15-.675.7-1.088T5.825 5H7V4h3v1h4zm2.8 8q.575-1.1 1.213-2.45T19 7H5.825q-.275 1.175-.788 2.538T4 12zM19 7H5.825zm0 10H6z");
}

</style>
