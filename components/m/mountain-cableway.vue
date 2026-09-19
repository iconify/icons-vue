<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k1znyqb2w"/><g class="jeunsn1yj"><path class="y89sf-s2o"/><circle class="s9r3ph-4x"/></g><circle class="hgx1fabfo"/><circle class="efrxzwt5v"/><circle class="nlwe_ganc"/><path class="k96whp5jz"/><path class="x_lmtyuiz"/><path class="mgnc77b-y"/><path class="rw-o4_yqn"/><path class="iihnmh2rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:mountain-cableway" /></template>
<style>
.efrxzwt5v {
  cx: 42.2px;
  cy: 8.6px;
  r: 2.8px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.hgx1fabfo {
  cx: 21.8px;
  cy: 4.8px;
  r: 0.9px;
  fill: var(--svg-color--94989b, #94989b);
}

.iihnmh2rz {
  fill: var(--svg-color--dae3ea, #dae3ea);
  d: path("M61.1 55.8c.3-.7.5-1.3.7-2.1H2.2c.1.7.4 1.4.7 2.1zM43.9 21.5H48v27h-4.1zm-13.9 0h4.1v27H30zm-14 0h4.1v27H16z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.k1znyqb2w {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M30.7 6.7h3.8v15h-3.8z");
}

.k96whp5jz {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M30.7 14.2h3.8v7.5h-3.8z");
}

.mgnc77b-y {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M57.9 47.5H6.1V32.8c0-4.7 3.8-8.5 8.5-8.5h34.9c4.7 0 8.5 3.8 8.5 8.5z");
}

.nlwe_ganc {
  cx: 42.2px;
  cy: 8.6px;
  r: 0.9px;
  fill: var(--svg-color--94989b, #94989b);
}

.rw-o4_yqn {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M62 51.7C62 57.4 57.4 62 51.7 62H12.3C6.6 62 2 57.4 2 51.7z");
}

.s9r3ph-4x {
  cx: 21.8px;
  cy: 4.8px;
  r: 2.8px;
}

.x_lmtyuiz {
  fill: var(--svg-color--dae3ea, #dae3ea);
  d: path("M62 51.7C62 57.4 57.4 62 51.7 62H12.3C6.6 62 2 57.4 2 51.7V30.8c0-5.7 4.6-10.3 10.3-10.3h39.5c5.7 0 10.3 4.6 10.3 10.3v20.9z");
}

.y89sf-s2o {
  d: path("M62 17L2 5.8V3.9l60 11.2zM42.3 9.5L21.7 5.8V3.9l20.6 3.7z");
}

</style>
