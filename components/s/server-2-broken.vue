<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b073u-bnc"/><path class="z_x8n2b5o"/><path class="wmv_g2b0a"/><path class="sob1app1w"/><path class="qcji_nb3a"/><path class="drih6ob2s"/><path class="dbda7jb-a"/><path class="nu5dhcc1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-2-broken" /></template>
<style>
.b073u-bnc {
  d: path("M13 21H6C4.11438 21 3.17157 21 2.58579 20.4142C2 19.8284 2 18.8856 2 17C2 15.1144 2 14.1716 2.58579 13.5858C3.17157 13 4.11438 13 6 13H18C19.8856 13 20.8284 13 21.4142 13.5858C22 14.1716 22 15.1144 22 17C22 18.8856 22 19.8284 21.4142 20.4142C20.8284 21 19.8856 21 18 21H17");
}

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

.qcji_nb3a {
  d: path("M9 7L9 5");
}

.sob1app1w {
  d: path("M6 7L6 5");
}

.wmv_g2b0a {
  d: path("M13.5 6L18 6");
}

.z_x8n2b5o {
  d: path("M11 2H18C19.8856 2 20.8284 2 21.4142 2.58579C22 3.17157 22 4.11438 22 6C22 7.88562 22 8.82843 21.4142 9.41421C20.8284 10 19.8856 10 18 10H6C4.11438 10 3.17157 10 2.58579 9.41421C2 8.82843 2 7.88562 2 6C2 4.11438 2 3.17157 2.58579 2.58579C3.17157 2 4.11438 2 6 2H7");
}

</style>
