<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f71t4nbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subtitles-off-sharp" /></template>
<style>
.f71t4nbqc {
  fill: currentColor;
  d: path("M18 10h-5.15l-6-6H22v15.15L14.85 12H18zm2.55 13.35L17.15 20H2V4h2v2.8L.65 3.45l1.4-1.4l19.9 19.9zM6 12h2v-1.2l-.8-.8H6zm5.15 2H6v2h7.15z");
}

</style>
