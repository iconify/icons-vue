<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="agb-3rbzx"/><path class="avb7gtbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parallel-parking" /></template>
<style>
.agb-3rbzx {
  d: path("M4.25 12H2.5V8.5l2.5-1l2.25-3.75H13l2.75 3.75L18 8v4h-1m-4 0H8.25");
}

.avb7gtbug {
  d: path("M4.25 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm12.36 1.186q.19-.258.29-.562T17 12q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T15 10t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T13 12q0 .088.008.175q.007.087.023.174q.015.086.038.17q.022.085.052.167q.031.083.068.162t.081.155t.094.148q.051.071.107.138q.057.067.119.129t.129.118t.139.106t.148.094q.076.043.156.08t.162.066t.167.052t.171.037M2.5 17h12m3 5v-6h2a2 2 0 0 1 0 4h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
