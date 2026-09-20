<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vngo37z9r"/><path class="sj_5geaal"/><path class="sb4_t8bif"/><path class="k3dde5b8r"/><path class="p2o-cbcpp"/><path class="ffc0876bs"/><path class="ef6_6hbid"/><path class="pjm2hcc9q"/><path class="i6bme6cxu"/><path class="sjl57-bdj"/><path class="h21rio5ca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sakai" /></template>
<style>
.ef6_6hbid {
  fill: var(--svg-color--48b081, #48b081);
  d: path("m12 7.5l4 2.25v4.5l-4 2.25z");
}

.ffc0876bs {
  fill: var(--svg-color--bce784, #bce784);
  d: path("M16 5.25L12 7.5L8 5.25L12 3z");
}

.ft5dv1b6b {
  fill: none;
}

.h21rio5ca {
  fill: var(--svg-color--348aa7, #348aa7);
  d: path("M16 9.75v-4.5l4 2.25z");
}

.i6bme6cxu {
  fill: var(--svg-color--57c795, #57c795);
  d: path("M16 5.25L12 7.5l4 2.25z");
}

.k3dde5b8r {
  fill: var(--svg-color--76e8b5, #76e8b5);
  d: path("m8 5.25l4 2.25l-4 2.25z");
}

.p2o-cbcpp {
  fill: var(--svg-color--12556b, #12556b);
  d: path("m4 16.5l4-2.25l4 2.25V21z");
}

.pjm2hcc9q {
  fill: var(--svg-color--1a6882, #1a6882);
  d: path("m20 7.5l-4 2.25v4.5l4 2.25z");
}

.sb4_t8bif {
  fill: var(--svg-color--1a6882, #1a6882);
  d: path("m4 7.5l4 2.25v4.5L4 16.5z");
}

.sj_5geaal {
  fill: var(--svg-color--55cf98, #55cf98);
  d: path("M12 7.5L8 9.75v4.5l4 2.25z");
}

.sjl57-bdj {
  fill: var(--svg-color--0d3e4f, #0d3e4f);
  d: path("m20 16.5l-4-2.25l-4 2.25V21z");
}

.vngo37z9r {
  fill: var(--svg-color--348aa7, #348aa7);
  d: path("M8 9.75v-4.5L4 7.5z");
}

</style>
