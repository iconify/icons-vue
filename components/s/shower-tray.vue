<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1c2ckr_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shower-tray" /></template>
<style>
.c1c2ckr_v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 4.25h13q.061 0 .122.01q.06.01.118.03t.112.048q.055.029.103.066q.049.037.091.082q.042.044.076.095t.06.107q.025.056.042.115l3 11q.026.097.026.197v3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19v-3q0-.1.026-.197l3-11q.017-.059.042-.115t.06-.107q.034-.051.076-.095t.091-.082q.048-.037.103-.066t.112-.048t.118-.03q.061-.01.122-.01m2.75 6.25Q8.25 13 12 13t3.75-2.5T12 8t-3.75 2.5");
}

</style>
