<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGf21SaeHz" class="l-u-4wbyu"/><path id="SVGnCeeMcOU" class="u9bgmvvqq"/></defs><use href="#SVGf21SaeHz" class="n1mjunbsu"/><path class="uoo1rnatk"/><circle class="nqe8vabox"/><path class="ow2apnakg"/><circle transform="rotate(-29.988 39.033 20.76)" class="v3hx-6jha"/><path class="bqzcf7b6r"/><g class="ehej3-bmx"><use href="#SVGnCeeMcOU"/><use href="#SVGnCeeMcOU"/></g><path class="he0t3gbis"/><ellipse class="pi75tgbcl"/><path class="ekw8s0b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:ten-thirty" /></template>
<style>
.bqzcf7b6r {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M17.56 37.19a3.69 3.69 0 0 1 5.04-1.34a3.67 3.67 0 0 1 1.34 5.03a3.673 3.673 0 0 1-5.03 1.35a3.703 3.703 0 0 1-1.35-5.04M10.38 64a3.675 3.675 0 1 1 7.35 0c0 2.04-1.64 3.69-3.67 3.69c-2.03-.01-3.69-1.65-3.68-3.69m7.18 26.81c-1.01-1.77-.41-4.02 1.35-5.03a3.68 3.68 0 1 1 3.67 6.38c-1.75 1.01-4 .41-5.02-1.35m19.63 19.63a3.69 3.69 0 0 1-1.35-5.03a3.694 3.694 0 0 1 5.04-1.35a3.673 3.673 0 0 1 1.35 5.03c-1.03 1.76-3.29 2.37-5.04 1.35m53.61 0a3.68 3.68 0 0 1-5.03-1.35a3.68 3.68 0 0 1 1.33-5.03c1.77-1.02 4.03-.42 5.04 1.34a3.68 3.68 0 0 1-1.34 5.04m19.63-19.63a3.69 3.69 0 0 1-5.03 1.35a3.67 3.67 0 0 1-1.35-5.03a3.68 3.68 0 0 1 5.03-1.35c1.76 1.01 2.37 3.28 1.35 5.03M59.4 60.61h9.2v56.05h-9.2z");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.ekw8s0b-v {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M90.81 17.57a3.68 3.68 0 0 1 1.34 5.03a3.67 3.67 0 0 1-5.03 1.35a3.68 3.68 0 0 1-1.34-5.03a3.67 3.67 0 0 1 5.03-1.35m-26.82-7.19c-2.03 0-3.68 1.65-3.68 3.68a3.685 3.685 0 0 0 7.37 0c0-2.03-1.65-3.69-3.69-3.68");
}

.he0t3gbis {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m69.67 63.15l-6.5 6.52l-26.01-25.9l6.5-6.53z");
}

.l-u-4wbyu {
  d: path("M64 6.26C32.17 6.26 6.27 32.17 6.27 64s25.9 57.73 57.73 57.73s57.74-25.9 57.74-57.73S95.83 6.26 64 6.26");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nqe8vabox {
  cx: 113.93px;
  cy: 64px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.ow2apnakg {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M110.43 37.2c1.02 1.76.41 4.01-1.35 5.03a3.67 3.67 0 0 1-5.03-1.35a3.677 3.677 0 0 1 1.35-5.03a3.67 3.67 0 0 1 5.03 1.35M90.81 17.57a3.68 3.68 0 0 1 1.34 5.03a3.67 3.67 0 0 1-5.03 1.35a3.68 3.68 0 0 1-1.34-5.03a3.67 3.67 0 0 1 5.03-1.35");
}

.pi75tgbcl {
  cx: 64px;
  cy: 64.01px;
  fill: var(--svg-color--fff, #fff);
  rx: 3.69px;
  ry: 3.68px;
}

.u9bgmvvqq {
  d: path("M73.78 63.99c0 5.41-4.39 9.79-9.78 9.79c-5.4 0-9.78-4.38-9.78-9.79c0-5.4 4.38-9.77 9.78-9.77c5.39 0 9.78 4.38 9.78 9.77");
}

.uoo1rnatk {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 127.89C28.77 127.89.1 99.23.1 64S28.77.11 64 .11s63.89 28.66 63.89 63.9c0 35.22-28.66 63.88-63.89 63.88M64 6.26C32.17 6.26 6.27 32.17 6.27 64s25.9 57.73 57.73 57.73s57.74-25.9 57.74-57.73S95.83 6.26 64 6.26");
}

.v3hx-6jha {
  cx: 39.03px;
  cy: 20.76px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

</style>
