<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb4sz3n_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-sunblock-sharp" /></template>
<style>
.hb4sz3n_j {
  fill: currentColor;
  d: path("M2 7V4h2v3zm0 13v-3h2v3zM7.25 9.175L5.825 7.75L7.95 5.625L9.375 7.05zm.7 9.2L5.825 16.25l1.425-1.425l2.125 2.125zM8 13v-2h6l-1.8-2.4l1.6-1.2L18 13zm11 6V5h3v14zM2 16v-2q.825 0 1.413-.587T4 12t-.587-1.412T2 10V8q1.65 0 2.825 1.175T6 12t-1.175 2.825T2 16");
}

</style>
