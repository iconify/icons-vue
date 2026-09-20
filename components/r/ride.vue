<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e7jmbeb8b"/><path fill="url(#SVGaOeVgceX)" class="zm_co7b7g"/><path class="pk04ctzzt"/><path fill="url(#SVGevorYdln)" class="q9j8l14uq"/><path class="len4lcbzx"/><defs><linearGradient id="SVGaOeVgceX" x1="3.992" x2="37.083" y1="13.886" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="e4n0_jbwm"/><stop offset="1" class="sno87lbnw"/></linearGradient><linearGradient id="SVGevorYdln" x1="6.697" x2="19.142" y1="17.501" y2="9.619" gradientUnits="userSpaceOnUse"><stop class="hjy77cbvf"/><stop offset="1" class="fcbro_07e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ride" /></template>
<style>
.e4n0_jbwm {
  stop-color: var(--svg-color--4bdaf7, #4bdaf7);
}

.e7jmbeb8b {
  fill: var(--svg-color--f11e99, #f11e99);
  d: path("M3.77 6.602c1.905-2.187 6.278-1.112 8.046-.34c-.127-.48.407-1.487 3.568-1.661c3.943-.212 6.267 3.594 5.452 6.008c-.805 2.408-1.89 1.604-2.541 3.97c-.646 2.355-1.816 5.119-4.076 5.876c-1.678.56-4.23 1.222-7.792-1.027c-2.858-1.8-2.107-4.854-1.366-5.929c-1.1-1.355-3.192-4.711-1.291-6.897");
}

.fcbro_07e {
  stop-color: var(--svg-color--781390, #781390);
}

.ft5dv1b6b {
  fill: none;
}

.hjy77cbvf {
  stop-color: var(--svg-color--2424e5, #2424e5);
}

.len4lcbzx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.222 6.262c-3.16 0-5.711 2.54-5.711 5.664c0 3.112 2.551 5.653 5.711 5.653c3.155 0 5.707-2.54 5.707-5.658s-2.546-5.66-5.707-5.66M3.78 11.926c0-4.092 3.335-7.395 7.442-7.395c4.103 0 7.438 3.303 7.438 7.39c0 4.091-3.335 7.39-7.438 7.39a7.414 7.414 0 0 1-7.442-7.39z");
}

.pk04ctzzt {
  fill: var(--svg-color--873dee, #873dee);
  d: path("M19.634 16.575c-1.413 3.546-5.15 3.229-7.808 3.229c-1.884 0-4.271.619-5.674-.64a5 5 0 0 1-1.44-2.05C3.67 14.06 5.93 13.43 6.205 11.715c.27-1.725-5.479-9.062 4.018-8.702c10.11.386 10.82 10.01 9.411 13.562");
}

.q9j8l14uq {
  d: path("M20.137 12.022a4.7 4.7 0 0 1-.587.582a3.4 3.4 0 0 0-1.229 1.985c-.497 1.81-1.307 3.864-2.683 5.06c-1.059.186-2.17.175-3.176.165h-.614c-.514 0-1.07.058-1.63.116c-1.006.106-2.044.223-2.912 0q-.42-.214-.858-.492a5 5 0 0 1-.72-.545a6.7 6.7 0 0 1-1.26-2.26a4.63 4.63 0 0 1 .218-2.33c.19-.344.428-.65.667-.953c.397-.518.778-1.016.873-1.625c.064-.413-.212-1.148-.55-2.022c-.45-1.175-.996-2.604-.922-3.843c2.15-1.127 5.57-.243 7.083.418c-.127-.487.408-1.492 3.568-1.662c.159-.01.312-.016.466-.01c2.805 1.773 3.996 4.732 4.266 7.41z");
}

.sno87lbnw {
  stop-color: var(--svg-color--6a63e3, #6a63e3);
}

.zm_co7b7g {
  d: path("M3.733 17.613c-.757-1.948.783-3.547 1.651-4.108l4.346-1.387l2.69 7.178c-2.219.19-2.224.482-3.7.762c-1.472.276-4.04 0-4.987-2.44z");
}

</style>
