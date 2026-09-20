<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGCgSd4cZE" class="ncpdnetvp"/></defs><use href="#SVGCgSd4cZE" class="n1mjunbsu"/><path class="k9w5p6bay"/><circle class="nqe8vabox"/><path class="r-op7fz9m"/><circle transform="rotate(-30 39.032 20.76)" class="v3hx-6jha"/><path class="q68hlpbme"/><g class="ehej3-bmx"><circle class="s3oe30a1p"/><path class="foyxifbyu"/><circle class="s3oe30a1p"/></g><path class="tq4a0ts_y"/><ellipse class="n5-iubygd"/><path class="rlrllybuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:three-thirty" /></template>
<style>
.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.foyxifbyu {
  d: path("M59.4 60.6h9.21v56.06H59.4z");
}

.k9w5p6bay {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 127.9C28.77 127.9.1 99.23.1 64S28.77.1 64 .1s63.9 28.67 63.9 63.9s-28.67 63.9-63.9 63.9M64 6.26C32.17 6.26 6.27 32.17 6.27 64s25.9 57.73 57.74 57.73s57.73-25.9 57.73-57.73C121.73 32.17 95.84 6.26 64 6.26");
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

.ncpdnetvp {
  d: path("M64 6.26C32.17 6.26 6.27 32.17 6.27 64s25.9 57.73 57.74 57.73s57.73-25.9 57.73-57.73C121.73 32.17 95.84 6.26 64 6.26");
}

.nqe8vabox {
  cx: 113.93px;
  cy: 64px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.q68hlpbme {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M17.57 37.19a3.68 3.68 0 0 1 5.03-1.34a3.68 3.68 0 0 1 1.35 5.02a3.683 3.683 0 0 1-5.04 1.35a3.677 3.677 0 0 1-1.34-5.03M10.38 64c0-2.04 1.65-3.68 3.68-3.68c2.04 0 3.68 1.64 3.68 3.67c0 2.04-1.65 3.69-3.68 3.69A3.67 3.67 0 0 1 10.38 64m7.18 26.81c-1.01-1.77-.41-4.02 1.35-5.03a3.69 3.69 0 0 1 5.04 1.34c1.02 1.77.41 4.02-1.35 5.04a3.694 3.694 0 0 1-5.04-1.35m19.63 19.63a3.69 3.69 0 0 1-1.35-5.03a3.695 3.695 0 0 1 5.04-1.36a3.69 3.69 0 0 1 1.35 5.04a3.694 3.694 0 0 1-5.04 1.35m53.61 0c-1.76 1.01-4.02.41-5.03-1.35a3.67 3.67 0 0 1 1.35-5.03a3.67 3.67 0 0 1 5.03 1.35c1.02 1.76.42 4.02-1.35 5.03m19.63-19.63a3.68 3.68 0 0 1-5.03 1.35a3.673 3.673 0 0 1-1.35-5.03a3.68 3.68 0 0 1 5.03-1.35a3.673 3.673 0 0 1 1.35 5.03");
}

.r-op7fz9m {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M110.43 37.2c1.01 1.76.41 4.01-1.35 5.03a3.67 3.67 0 0 1-5.03-1.35a3.67 3.67 0 0 1 1.35-5.03a3.67 3.67 0 0 1 5.03 1.35M90.81 17.57a3.68 3.68 0 0 1 1.35 5.03a3.673 3.673 0 0 1-5.03 1.35a3.68 3.68 0 0 1-1.35-5.03a3.67 3.67 0 0 1 5.03-1.35");
}

.rlrllybuh {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 10.38c-2.04 0-3.68 1.65-3.68 3.68s1.64 3.68 3.68 3.68s3.69-1.65 3.69-3.68c-.01-2.03-1.66-3.69-3.69-3.68");
}

.s3oe30a1p {
  cx: 64px;
  cy: 64px;
  r: 9.78px;
}

.tq4a0ts_y {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m59.52 67.56l2.38-8.88l35.45 9.49l-2.38 8.91z");
}

.v3hx-6jha {
  cx: 39.03px;
  cy: 20.76px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

</style>
