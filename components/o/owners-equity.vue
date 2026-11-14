<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ahxv6gf7h"/><path class="zs0rwlb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:owners-equity" /></template>
<style>
.ahxv6gf7h {
  d: path("M14.815 12H10V4.5q-.184 0-.368.009t-.367.027t-.365.045t-.363.063t-.359.081t-.355.098t-.35.115t-.343.133t-.337.149q-.166.079-.328.166q-.163.086-.321.181t-.311.197t-.301.212t-.29.226t-.279.241t-.266.254t-.254.266t-.241.279t-.226.29t-.212.301t-.197.311t-.181.321t-.166.328q-.079.167-.149.337q-.071.17-.133.343t-.115.35t-.098.355t-.081.359t-.063.363t-.045.365t-.027.367T2.5 12t.009.368t.027.367t.045.365t.063.363t.081.359t.098.355t.115.35t.133.343t.149.337q.079.166.166.328q.086.163.181.321t.197.311t.212.301t.226.29t.241.279t.254.266t.266.254t.279.241t.29.226t.301.212t.311.197t.321.181q.162.087.328.166q.167.079.337.149q.17.071.343.133t.35.115t.355.098t.359.081t.363.063t.365.045t.367.027t.368.009q1.202 0 2.344-.376");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zs0rwlb2k {
  d: path("M12 10V2.5a7.5 7.5 0 0 1 7.5 7.5Zm4.25 5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1.75 6.5c0-1.5 1.5-2.25 3.5-2.25s3.5.75 3.5 2.25");
}

</style>
