<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rs-uyo2ps"/><path class="vljuhaccy"/><g class="y9tr6bcfx"><path class="y3cihvb5d"/><path class="o-c4k6bus"/></g><g class="y9tr6bcfx"><path class="zstph6boj"/><path class="xmke0yb8i"/></g><path class="yduk_hb2z"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sanitas-portal" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o-c4k6bus {
  d: path("M13.234 22.45c.482-.483.82-.525 1.75-.525c1.056 0 1.75.465 1.75 1.72v3.58");
}

.rs-uyo2ps {
  cx: 25.807px;
  cy: 19.475px;
  r: 0.7px;
  fill: currentColor;
}

.vljuhaccy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.807 21.925v5.3m-18.566-.447c.365.306.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325s-.592-1.325-1.322-1.325h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447m26.939 4.406c.364.306.758.447 1.644.447h.449c.73 0 1.322-.593 1.322-1.325s-.592-1.325-1.322-1.325h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447M28.26 20.275v5.95a1 1 0 0 0 1 1h.3m-1.3-5.3h1.05m-6.302 5.3v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3");
}

.xmke0yb8i {
  d: path("M31.92 22.45c.482-.483.82-.525 1.75-.525c1.056 0 1.75.465 1.75 1.72v3.58");
}

.y3cihvb5d {
  d: path("M16.73 25.225c0 1.105-.889 2-1.985 2h-.696c-.726 0-1.315-.593-1.315-1.325s.589-1.325 1.315-1.325h2.685");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yduk_hb2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.757 21.925h1.05");
}

.zstph6boj {
  d: path("M35.416 25.225c0 1.105-.888 2-1.984 2h-.697c-.726 0-1.315-.593-1.315-1.325s.589-1.325 1.315-1.325h2.685");
}

</style>
