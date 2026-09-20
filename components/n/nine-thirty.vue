<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG2eGeibPG" class="cerdgdcfb"/><path id="SVGmQeVXd4n" class="q3ihu16mn"/></defs><use href="#SVG2eGeibPG" class="n1mjunbsu"/><path class="rxh_acr-k"/><path class="d_mh9egiz"/><circle transform="rotate(-60 20.755 39.034)" class="epcti1vdw"/><path class="eqlu1nbjr"/><g class="ehej3-bmx"><use href="#SVGmQeVXd4n"/><use href="#SVGmQeVXd4n"/></g><path class="rpc7lkb-f"/><path class="hum1ueb7p"/><path class="d01vaqbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:nine-thirty" /></template>
<style>
.cerdgdcfb {
  d: path("M64 6.27c-31.84 0-57.73 25.9-57.73 57.74c0 31.83 25.89 57.72 57.73 57.72c31.83 0 57.73-25.89 57.73-57.72c0-31.84-25.9-57.74-57.73-57.74");
}

.d_mh9egiz {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M117.62 64.01a3.685 3.685 0 1 1-7.37-.01a3.685 3.685 0 0 1 7.37.01m-7.19-26.82a3.7 3.7 0 0 1-1.35 5.04a3.69 3.69 0 0 1-5.03-1.35a3.683 3.683 0 0 1 1.35-5.04c1.76-1.01 4.02-.4 5.03 1.35M90.81 17.57a3.677 3.677 0 0 1 1.34 5.03c-1.01 1.76-3.27 2.36-5.03 1.35c-1.76-1.02-2.37-3.28-1.35-5.03a3.694 3.694 0 0 1 5.04-1.35m-53.62-.01a3.69 3.69 0 0 1 5.03 1.35c1.02 1.77.42 4.02-1.35 5.03a3.67 3.67 0 0 1-5.03-1.35a3.685 3.685 0 0 1 1.35-5.03");
}

.d01vaqbdm {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 10.38c-2.04 0-3.68 1.65-3.69 3.68c0 2.04 1.64 3.68 3.67 3.68c2.04 0 3.7-1.65 3.69-3.68A3.67 3.67 0 0 0 64 10.38");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.epcti1vdw {
  cx: 20.76px;
  cy: 39.03px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.eqlu1nbjr {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M10.38 64c0-2.03 1.65-3.68 3.68-3.68c2.04 0 3.68 1.65 3.68 3.68s-1.65 3.69-3.68 3.68c-2.03 0-3.69-1.65-3.68-3.68m7.18 26.81a3.68 3.68 0 0 1 1.35-5.03a3.696 3.696 0 0 1 5.04 1.35c1.02 1.77.41 4.02-1.35 5.03a3.694 3.694 0 0 1-5.04-1.35m19.63 19.62a3.68 3.68 0 0 1-1.35-5.03a3.673 3.673 0 0 1 5.03-1.35a3.673 3.673 0 0 1 1.35 5.03c-1.01 1.76-3.27 2.38-5.03 1.35m53.61 0a3.677 3.677 0 0 1-5.03-1.35a3.67 3.67 0 0 1 1.34-5.03c1.75-1.01 4.02-.41 5.03 1.35c1.03 1.77.43 4.02-1.34 5.03m19.63-19.61a3.68 3.68 0 0 1-5.03 1.34a3.66 3.66 0 0 1-1.35-5.02a3.67 3.67 0 0 1 5.03-1.35a3.67 3.67 0 0 1 1.35 5.03M59.4 60.61h9.2v56.06h-9.2z");
}

.hum1ueb7p {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.69 64.01c0 2.03-1.65 3.68-3.69 3.68a3.685 3.685 0 1 1 0-7.37c2.04 0 3.69 1.65 3.69 3.69");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.q3ihu16mn {
  d: path("M73.79 63.99c0 5.41-4.38 9.79-9.78 9.79s-9.78-4.38-9.78-9.79c0-5.39 4.38-9.77 9.78-9.77c5.39 0 9.78 4.38 9.78 9.77");
}

.rpc7lkb-f {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m68.5 60.46l-2.4 8.87l-35.43-9.59l2.4-8.89z");
}

.rxh_acr-k {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 127.9C28.77 127.9.1 99.24.1 64.01C.1 28.77 28.77.1 64 .1s63.89 28.67 63.89 63.91C127.9 99.24 99.23 127.9 64 127.9M64 6.27c-31.84 0-57.73 25.9-57.73 57.74c0 31.83 25.89 57.72 57.73 57.72c31.83 0 57.73-25.89 57.73-57.72c0-31.84-25.9-57.74-57.73-57.74");
}

</style>
