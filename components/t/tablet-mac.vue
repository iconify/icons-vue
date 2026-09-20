<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxpjbtl0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-mac" /></template>
<style>
.gxpjbtl0b {
  fill: currentColor;
  d: path("M12.54 19.809q.23-.23.23-.54t-.23-.54q-.23-.229-.54-.229t-.54.23t-.23.54t.23.539t.54.23t.54-.23M5.616 22q-.672 0-1.144-.472T4 20.385V3.615q0-.67.472-1.143Q4.944 2 5.616 2h12.769q.67 0 1.143.472q.472.472.472 1.144v16.769q0 .67-.472 1.143q-.472.472-1.143.472zM5 16.538h14V5.5H5z");
}

</style>
