<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGia4HFcow" class="lng6uobqb"/><path id="SVGr7dyBdIt" class="y9ij_qb3p"/></defs><use href="#SVGia4HFcow" class="n1mjunbsu"/><path class="s4zdhhbwk"/><circle class="nqe8vabox"/><path class="ukl-vjbhe"/><g class="ehej3-bmx"><use href="#SVGr7dyBdIt"/><use href="#SVGr7dyBdIt"/></g><path class="t1v3qxb3p"/><ellipse class="n5-iubygd"/><path class="cpyu0cb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:two-thirty" /></template>
<style>
.cpyu0cb3g {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M63.99 10.38c-2.03 0-3.68 1.65-3.68 3.68s1.64 3.68 3.68 3.68s3.69-1.65 3.69-3.68s-1.65-3.69-3.69-3.68");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.lng6uobqb {
  d: path("M64 6.26C32.16 6.26 6.27 32.17 6.27 64s25.9 57.73 57.73 57.73s57.73-25.9 57.73-57.73S95.83 6.26 64 6.26");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n5-iubygd {
  cx: 64px;
  cy: 64px;
  fill: var(--svg-color--fff, #fff);
  rx: 3.69px;
  ry: 3.68px;
}

.nqe8vabox {
  cx: 113.93px;
  cy: 64px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.s4zdhhbwk {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 127.89C28.76 127.89.1 99.23.1 64C.1 28.76 28.76.1 64 .1s63.9 28.66 63.9 63.9c0 35.23-28.67 63.89-63.9 63.89M64 6.26C32.16 6.26 6.27 32.17 6.27 64s25.9 57.73 57.73 57.73s57.73-25.9 57.73-57.73S95.83 6.26 64 6.26");
}

.t1v3qxb3p {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m59.512 60.423l35.456-9.472l2.377 8.898l-35.456 9.472z");
}

.ukl-vjbhe {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M110.43 37.2c1.02 1.76.41 4.01-1.35 5.03c-1.76 1.01-4.02.42-5.03-1.35a3.677 3.677 0 0 1 1.35-5.03a3.673 3.673 0 0 1 5.03 1.35M90.8 17.57c1.76 1.02 2.37 3.27 1.35 5.03s-3.27 2.37-5.03 1.35s-2.37-3.28-1.35-5.03a3.673 3.673 0 0 1 5.03-1.35m-53.61 0a3.673 3.673 0 0 1 5.03 1.35a3.68 3.68 0 1 1-6.37 3.68c-1.02-1.77-.43-4.02 1.34-5.03M17.56 37.19a3.69 3.69 0 0 1 5.03-1.35c1.76 1.02 2.37 3.28 1.35 5.03a3.673 3.673 0 0 1-5.03 1.35a3.677 3.677 0 0 1-1.35-5.03M10.38 64c0-2.03 1.65-3.68 3.68-3.68c2.04 0 3.68 1.65 3.68 3.68a3.67 3.67 0 0 1-3.68 3.68c-2.03 0-3.69-1.64-3.68-3.68m7.18 26.81c-1.01-1.77-.41-4.02 1.35-5.03a3.69 3.69 0 0 1 5.04 1.34c1.02 1.77.41 4.02-1.35 5.04c-1.77 1.01-4.03.41-5.04-1.35m19.63 19.62a3.69 3.69 0 0 1-1.35-5.03a3.68 3.68 0 0 1 5.03-1.35a3.68 3.68 0 0 1 1.35 5.03a3.676 3.676 0 0 1-5.03 1.35m53.61 0a3.673 3.673 0 0 1-5.03-1.35a3.663 3.663 0 0 1 1.34-5.02a3.677 3.677 0 0 1 5.03 1.34c1.03 1.77.42 4.02-1.34 5.03m19.63-19.62a3.69 3.69 0 0 1-5.03 1.35a3.67 3.67 0 0 1-1.35-5.03a3.68 3.68 0 0 1 5.03-1.35a3.68 3.68 0 0 1 1.35 5.03M59.4 60.61h9.21v56.05H59.4z");
}

.y9ij_qb3p {
  d: path("M73.78 63.99c0 5.41-4.38 9.79-9.78 9.79s-9.78-4.38-9.78-9.79c0-5.39 4.38-9.77 9.78-9.77s9.78 4.37 9.78 9.77");
}

</style>
