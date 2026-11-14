<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6kw7ac4z"/><path class="rbj0n_o9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-branch-add" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbj0n_o9q {
  d: path("m7 9l1-3.5h8L17 9M7 9a1.25 1.25 0 0 0 2.5 0A1.25 1.25 0 0 0 12 9a1.25 1.25 0 0 0 2.5 0A1.25 1.25 0 0 0 17 9m-8.5 2.5v2h6.9m.1-.2v-1.8m2.5 3v7M14.5 18h7");
}

.w6kw7ac4z {
  d: path("M13.16 20.41A27 27 0 0 1 12 21.5S4.5 15 4.5 9.5q0-.184.009-.368t.027-.367t.045-.365t.063-.363t.081-.359t.098-.355t.115-.35t.133-.343t.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29t.241-.279t.254-.266t.266-.254t.279-.241t.29-.226t.301-.212t.311-.197t.321-.181t.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027T12 2t.368.009t.367.027t.365.045t.363.063t.359.081t.355.098t.35.115t.343.133t.337.149q.166.079.328.166q.163.086.321.181t.311.197t.301.212t.29.226q.142.117.279.241q.136.124.266.254t.254.266t.241.279q.116.142.226.29t.212.301t.197.311t.181.321q.087.162.166.328q.079.167.149.337q.071.17.133.343t.115.35t.098.355t.081.359t.063.363t.045.365t.027.367t.009.368c0 .803-.16 1.628-.433 2.451");
}

</style>
