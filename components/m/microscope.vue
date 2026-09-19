<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xox0r3yrn"/><path class="vewh05b4h"/><path class="xjngk-b_l"/><path class="auo8nrvox"/><g class="j9357eg9x"><path class="g564mn0ez"/><ellipse class="u-wccmmla"/></g><g class="tybcrmi-m"><path class="f8s0cdcku"/><circle class="n2mc3tbzi"/><path class="e_h47hbru"/></g><path class="f_gjx5m5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:microscope" /></template>
<style>
.auo8nrvox {
  fill: var(--svg-color--333, #333);
  d: path("m52.5 11.4l-6.3-7.3L48.7 2L55 9.4z");
}

.e_h47hbru {
  d: path("m8.966 31.682l1.13-1.132L21.63 42.07l-1.13 1.132z");
}

.f_gjx5m5m {
  fill: var(--svg-color--29abe2, #29abe2);
  d: path("m10.174 30.528l1.13-1.132l11.535 11.52l-1.131 1.131z");
}

.f8s0cdcku {
  d: path("M36.2 26.7c1.7.6 3.5-.3 4.1-2s-.3-3.5-2-4.1s-3.5.3-4.1 2c-.6 1.6.3 3.5 2 4.1");
}

.g564mn0ez {
  d: path("M43.3 25.8c-1.2 3.4-4.9 5.1-8.3 3.9s-5.2-4.9-4-8.2s4.9-5.1 8.3-3.9s5.2 4.9 4 8.2");
}

.j9357eg9x {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

.n2mc3tbzi {
  cx: 33.5px;
  cy: 50.4px;
  r: 3.2px;
}

.tybcrmi-m {
  fill: var(--svg-color--333, #333);
}

.u-wccmmla {
  cx: 33.5px;
  cy: 50.4px;
  rx: 6.5px;
  ry: 6.4px;
}

.vewh05b4h {
  fill: var(--svg-color--333, #333);
  d: path("M44.6 47c-1.5-4.7-5.9-8.1-11.1-8.1s-9.6 3.4-11.1 8.1l-5.2 15h32.6zM19.2 27.1L43.8 6.2l6.3 7.3l-24.6 20.9z");
}

.xjngk-b_l {
  fill: var(--svg-color--94989b, #94989b);
  d: path("m24.3 33.1l-4-4.7l-1.9 2.5l3.2 3.7zm27.1-23l-4-4.7l-2.5 2.1l4 4.7z");
}

.xox0r3yrn {
  fill: var(--svg-color--94989b, #94989b);
  d: path("m24.6 54.3l-4.8-4.8c-6.1-6.1-2.2-10.4-2.2-10.4L13 34.5s-7.6 8.8 1.1 17.4l6.4 6.4zM33.7 44h7.2c4.8-10.9-1.6-24.6-1.7-24.9L33.4 22c0 .1 4.7 13.7.3 22");
}

</style>
