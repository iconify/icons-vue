<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGQ9ImBSfN"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="tsssa1bur"/><path class="dvr_e4qhb"/><path clip-rule="evenodd" class="wjpx14b_x"/><path class="oymo9f-op"/></g></mask></defs><circle mask="url(#SVGQ9ImBSfN)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:train-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.dvr_e4qhb {
  d: path("M11 15a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m7 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M7.581 18.147a1 1 0 1 1 1.841.782l-1.475 3.474a1 1 0 1 1-1.84-.781zm10.887-.494a1 1 0 0 0-1.876.694l1.47 3.97a1 1 0 0 0 1.876-.694z");
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

.oymo9f-op {
  d: path("M7.75 21.25v-1.5h10.501v1.5z");
}

.tsssa1bur {
  fill-rule: evenodd;
  d: path("M20.5 8a4 4 0 0 0-4-4h-7a4 4 0 0 0-4 4v6.99a4 4 0 0 0 2.814 3.82q2.338.725 4.686.726q2.348 0 4.686-.727a4 4 0 0 0 2.814-3.82zm-13 6.99V8a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v6.99a2 2 0 0 1-1.407 1.91a13.7 13.7 0 0 1-4.093.636q-2.041 0-4.093-.637A2 2 0 0 1 7.5 14.99");
}

.wjpx14b_x {
  fill-rule: evenodd;
  d: path("M18 9a2.5 2.5 0 0 0-2.5-2.5h-5A2.5 2.5 0 0 0 8 9v1.535a2.5 2.5 0 0 0 2.076 2.463q1.461.252 2.924.252t2.924-.252A2.5 2.5 0 0 0 18 10.535zm-8 1.535V9a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v1.535a.5.5 0 0 1-.415.492q-1.294.223-2.585.223t-2.585-.223a.5.5 0 0 1-.415-.492");
}

</style>
