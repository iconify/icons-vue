<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG1zZ7CFmz"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="s__bg4d6z"/><path clip-rule="evenodd" class="wz9z3_bee"/><path class="cy02kqb3i"/><path clip-rule="evenodd" class="rud44chzp"/><path class="ejo-kmp-r"/></g></mask></defs><circle mask="url(#SVG1zZ7CFmz)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:truck-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.cy02kqb3i {
  d: path("M13.25 11.75a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1zm0 2a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1zm0 2a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1z");
}

.ejo-kmp-r {
  d: path("M6.29 13.1H8a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H6a.5.5 0 0 1-.5-.5v-.85l.015-.122l.29-1.15a.5.5 0 0 1 .485-.378");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.rud44chzp {
  fill-rule: evenodd;
  d: path("M9 10.5H5.736a2 2 0 0 0-1.92 1.442L3 14.75V17a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-4.5a2 2 0 0 0-2-2M5 17v-1.966l.736-2.534H9V17z");
}

.s__bg4d6z {
  d: path("M10.5 21.75a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5m9 0a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5");
}

.wz9z3_bee {
  fill-rule: evenodd;
  d: path("M21 7.5H11a2 2 0 0 0-2 2V17a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V9.5a2 2 0 0 0-2-2M11 17V9.5h10V17z");
}

</style>
