<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q4lnojb5q"/><path class="weu35947f"/><path class="ll_1tdkdi"/><path class="wnxfr9pvb"/><path class="hgatnkb-l"/><path class="dl8nz-bbx"/><path class="a6oe2xblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sense" /></template>
<style>
.a6oe2xblr {
  fill: var(--svg-color--5da9ff, #5da9ff);
  d: path("m6.79 9.5l6.157-.5l-2.368-2.75z");
}

.dl8nz-bbx {
  fill: var(--svg-color--45c8fe, #45c8fe);
  d: path("m12.947 9l1.42-6l-3.789 3.25z");
}

.ft5dv1b6b {
  fill: none;
}

.hgatnkb-l {
  fill: var(--svg-color--6487e7, #6487e7);
  d: path("m6.79 9.499l4.445 5.5l1.712-6z");
}

.ll_1tdkdi {
  fill: var(--svg-color--8766f0, #8766f0);
  d: path("m13.421 17.998l3.79-3.25l-5.976.25z");
}

.q4lnojb5q {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.21 3H6.79v18h10.42z");
}

.weu35947f {
  fill: var(--svg-color--a367ff, #a367ff);
  d: path("M11.235 15L9.87 21l3.552-3z");
}

.wnxfr9pvb {
  fill: var(--svg-color--53539a, #53539a);
  d: path("m17.21 14.749l-4.262-5.75l-1.713 6z");
}

</style>
