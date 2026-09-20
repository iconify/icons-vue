<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zmyimdbdc"/><path class="vdlqio0ia"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xdb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vdlqio0ia {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.5 9c0 1.026.931 1.997 2 1.997s2-.97 2-1.997c0-1.026-.931-2-2-2s-2 .974-2 2m4-5H11v5.14c0 1.855-1.567 3.36-3.5 3.36S4 10.856 4 9s1.567-3.5 3.5-3.5c.717 0 1.445.178 2 .534zm9 11c0-1.027-.931-1.998-2-1.998s-2 .971-2 1.998c0 1.026.931 2.003 2 2.003s2-.977 2-2.003m-4 5H13v-5.139c0-1.857 1.567-3.361 3.5-3.361S20 13.144 20 15s-1.567 3.5-3.5 3.5c-.717 0-1.445-.203-2-.558zM15 6c1.026 0 2.002.931 2.002 2s-.976 2-2.002 2c-1.027 0-2-.932-2-2s.974-2 2-2m-.14-1.5c-1.857 0-3.361 1.567-3.361 3.5s1.644 3.5 3.5 3.5s3.5-1.567 3.5-3.5c0-.718-.202-1.445-.558-2H20V4.5zM7 16c0 1.068.974 2 2 2s1.997-.932 1.997-2s-.971-2-1.997-2s-2 .931-2 2m2.11 3.499L4 19.5V18h2.073a3.8 3.8 0 0 1-.573-2c0-1.933 1.644-3.5 3.5-3.5s3.5 1.567 3.5 3.5s-1.505 3.5-3.36 3.5z");
}

.zmyimdbdc {
  fill: var(--svg-color--278dc1, #278dc1);
  d: path("M24 0H0v24h24z");
}

</style>
