<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lsckfz6cr"/><path class="b6gyijb4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uv-indeks" /></template>
<style>
.b6gyijb4c {
  d: path("M18.435 25.18s-.276 2.164 1.16 2.3c1.436-.14 1.16-2.304 1.16-2.304m7.043-.036s-.277 2.163 1.16 2.3c1.435-.141 1.159-2.305 1.159-2.305m-14.054 6.279s2.25 4.758 8.349 5.016c6.1-.262 8.35-5.02 8.35-5.02");
}

.lsckfz6cr {
  d: path("m33.195 7.048l-18.514.054l-3.374 10.89l25.79-.147zm3.954 10.855l5.351 7.078l-37 .066l5.815-7.021m.028 7.154s-1.29 15.728 12.77 15.772c14.06-.078 12.77-15.805 12.77-15.805");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
