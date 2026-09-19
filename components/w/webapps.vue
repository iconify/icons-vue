<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8x1hn0sp"/><path class="khoi0gbfq"/><path class="t5zsl6b0k"/><ellipse class="z4_owib1s"/><path class="innkdzkwt"/><path class="bx04heb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:webapps" /></template>
<style>
.bx04heb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.27 19.798a2.74 2.74 0 0 1 1.22 2.15c0 1.658-1.094 2.472-2.97 2.472a4.29 4.29 0 0 1-3.714-2.183");
}

.innkdzkwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.51 18.624l1.032 6.254c0 .847 1.318 1.533 2.944 1.533s2.944-.686 2.944-1.533l1.033-6.254");
}

.j8x1hn0sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 20.816L23.495 9.266L4.5 20.233l20.005 11.55z");
}

.khoi0gbfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.332 21.49l-.001 6.929l-17.859 10.315L5.668 27.878l.001-6.97");
}

.t5zsl6b0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.501 22.547l-17.006-9.818l-15.996 9.236m16.973 16.769v-6.951");
}

.z4_owib1s {
  cx: 23.486px;
  cy: 18.624px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.977px;
  ry: 2.071px;
}

</style>
