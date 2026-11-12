<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q8-ccpb8y"/><path class="p_3twj84c"/><path class="wmv_g2b0a"/><path class="sob1app1w"/><path class="qcji_nb3a"/><path class="drih6ob2s"/><path class="dbda7jb-a"/><path class="nu5dhcc1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-2-linear" /></template>
<style>
.dbda7jb-a {
  d: path("M6 18L6 16");
}

.drih6ob2s {
  d: path("M13.5 17H18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nu5dhcc1j {
  d: path("M9 18L9 16");
}

.p_3twj84c {
  d: path("M6 10H18C19.8856 10 20.8284 10 21.4142 9.41421C22 8.82843 22 7.88562 22 6C22 4.11438 22 3.17157 21.4142 2.58579C20.8284 2 19.8856 2 18 2H6C4.11438 2 3.17157 2 2.58579 2.58579C2 3.17157 2 4.11438 2 6C2 7.88562 2 8.82843 2.58579 9.41421C3.17157 10 4.11438 10 6 10Z");
}

.q8-ccpb8y {
  d: path("M6 21H18C19.8856 21 20.8284 21 21.4142 20.4142C22 19.8284 22 18.8856 22 17C22 15.1144 22 14.1716 21.4142 13.5858C20.8284 13 19.8856 13 18 13H6C4.11438 13 3.17157 13 2.58579 13.5858C2 14.1716 2 15.1144 2 17C2 18.8856 2 19.8284 2.58579 20.4142C3.17157 21 4.11438 21 6 21Z");
}

.qcji_nb3a {
  d: path("M9 7L9 5");
}

.sob1app1w {
  d: path("M6 7L6 5");
}

.wmv_g2b0a {
  d: path("M13.5 6L18 6");
}

</style>
