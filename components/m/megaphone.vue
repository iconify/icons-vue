<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s9cq9_bru"/><path class="v8my7zbas"/><ellipse transform="rotate(-68.396 112.68 86.2)" class="qm6o__bjv"/><path class="ivljnacdk"/><path class="hgubk5woq"/><path class="v367rnbfu"/><ellipse transform="rotate(-68.396 27.547 52.493)" class="u0jy9cbrs"/><ellipse transform="rotate(-68.396 25.38 51.628)" class="qkw1iwbpd"/><linearGradient id="SVGKsy1gdRc" x1="-322.29" x2="-334.848" y1="45.871" y2="76.01" gradientTransform="translate(360.76 -25.673)" gradientUnits="userSpaceOnUse"><stop offset="0" class="u5oejccfr"/><stop offset="1" class="sfwvpobrb"/></linearGradient><path fill="url(#SVGKsy1gdRc)" class="b9mjrpbmb"/><path class="bjg6hk4lc"/><path class="oyvgv7tlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:megaphone" /></template>
<style>
.b9mjrpbmb {
  d: path("m14.36 47.256l22.05 8.74c7.55-19.08 8.74-36.5 2.65-38.91s-17.15 11.1-24.7 30.17");
}

.bjg6hk4lc {
  fill: var(--svg-color--fff, #fff);
  d: path("M45.65 39.94c-1.57-.56-1.59-2.01-1.36-3.12c1.02-4.99 1.36-10.25.92-14.07c-.13-1.12.2-2.18 1.32-2.31c1.13-.13 1.89 1.19 2.12 2.29c.82 4.05.93 9.23-.36 14.91c-.23 1-1.28 2.8-2.64 2.3");
}

.hgubk5woq {
  fill: var(--svg-color--ed3732, #ed3732);
  d: path("M14.36 47.26c-8.62 21.78-7.97 42.47 1.46 46.2l86.86 5.94c3.18 1.06 9.26-3.8 12.58-12.18s2.05-15.76-.63-17.6L47.04 14.59c-9.43-3.73-24.06 10.89-32.68 32.67");
}

.ivljnacdk {
  fill: var(--svg-color--82aec0, #82aec0);
  d: path("M106.06 102.88c2.58 1.02 5.67.02 8.56-2.42c0 0-5.25 1.37-5.93-3.38c0 0-5.31-4.06-7.27-2.58c.31 4.13 1.9 7.3 4.64 8.38");
}

.oyvgv7tlc {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M115.2 78.14c.26 1.51-1.3 1.12-2.14.7L57.68 50.05c-1.16-.59-4.87-2.05-5-3.94c-.21-3.04.09-5.06.35-7.4c.42-3.76 2.53-1.89 4.23-.76L113 75.47c.45.3 1.92 1.04 2.2 2.67");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.qkw1iwbpd {
  cx: 25.38px;
  cy: 51.628px;
  fill: var(--svg-color--2f7889, #2f7889);
  rx: 37.152px;
  ry: 11.861px;
}

.qm6o__bjv {
  cx: 112.68px;
  cy: 86.201px;
  fill: var(--svg-color--b8dade, #b8dade);
  rx: 17.951px;
  ry: 9.89px;
}

.s9cq9_bru {
  fill: var(--svg-color--82aec0, #82aec0);
  d: path("M53.23 107.21c-1.26-2.49-.52-5.55.57-8.31l3.47-8.77l7.98 2.78l-3.16 7.97c-.63 1.59-.15 3.28 2.78 3.59l10.5.76c.87.06 1.67-.45 1.99-1.26l2.95-7.45l6.28 1.31l-3.41 8.6c-1.61 4.08-3.09 5.43-7.62 5.53l-13.38-.54c-5.18-.22-7.5-1.34-8.95-4.21");
}

.sfwvpobrb {
  stop-color: var(--svg-color--353738, #353738);
  stop-opacity: 0;
}

.u0jy9cbrs {
  cx: 27.547px;
  cy: 52.493px;
  fill: var(--svg-color--b8dade, #b8dade);
  rx: 44.772px;
  ry: 18.081px;
}

.u5oejccfr {
  stop-color: var(--svg-color--353738, #353738);
}

.v367rnbfu {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M15.81 93.47c1.6.63 86.81 5.95 86.81 5.95c2.2.71 4.78-1.14 6.07-2.33c0 0-47.83-7.29-53.44-8.23c-20.51-3.42-25.61-3.63-22.42-8.34zm100.9-20.51s-.26-2.09-2.09-3.34l-67.8-55.37s2.49 3.14 3.14 4.51c.33.69.51 2.3.76 3.71c.48 2.7 2.49 4.26 3.89 5.27c10.32 7.47 51.72 37.44 62.1 45.22");
}

.v8my7zbas {
  fill: var(--svg-color--2f7889, #2f7889);
  d: path("m79.74 97.95l-1.87 4.72s1.03-1.19 3.66-.96c2.31.2 3.02 1.26 3.02 1.26l1.82-4.59zm-17.89 3.56s-1.03-1.71-3.49-1.87c-3.44-.23-5.29 1.32-5.29 1.32s.53-2.04 1.73-4.63l8.85.59z");
}

</style>
