<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oau-k-bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:microwave-gen" /></template>
<style>
.oau-k-bca {
  fill: currentColor;
  d: path("M4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zm1.269-2.884h8.23V7.885h-8.23zm12.27-.23q.23-.23.23-.54t-.23-.54t-.54-.229t-.539.23t-.23.54q0 .309.23.539t.54.23t.539-.23m-11.27-.77V8.885h6.23v6.23zm11.27-2.576q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23m0-3.347q.23-.23.23-.54q0-.309-.23-.538t-.54-.23t-.539.23t-.23.539t.23.54t.54.229q.309 0 .539-.23");
}

</style>
