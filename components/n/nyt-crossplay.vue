<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w497wpbwx"/><path class="h--f9ly8q"/><path class="adljfqbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nyt-crossplay" /></template>
<style>
.adljfqbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.727 14.618c.41-.173.801-.19 1.592.054l.183.058a1.236 1.236 0 0 1-.723 2.364m-.908-.278l.909.278");
}

.h--f9ly8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.233 28.288l-.02.065a5.502 5.502 0 1 1-10.524-3.218l1.64-5.36a5.502 5.502 0 1 1 10.524 3.218l-.02.064m6.691-4.504c.243.373.557.606 1.349.848l.184.057a1.236 1.236 0 0 0 .723-2.364");
}

.w497wpbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.393 6.424l22.574 6.901L36.065 35.9c-1.41 4.614-6.302 7.215-10.916 5.804l-14.214-4.345c-4.614-1.41-7.215-6.302-5.804-10.917l4.345-14.213c1.411-4.614 6.303-7.215 10.917-5.804");
}

</style>
