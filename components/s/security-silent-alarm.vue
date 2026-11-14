<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owok8ubvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-silent-alarm" /></template>
<style>
.owok8ubvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 14.5q0-.184.009-.368t.027-.367t.045-.365t.063-.363t.081-.359t.098-.355t.115-.35t.133-.343t.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29t.241-.279q.124-.136.254-.266t.266-.254q.137-.124.279-.241t.29-.226t.301-.212t.311-.197t.321-.181t.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027T12 7q.3 0 .598.024q.299.024.595.071q.296.048.587.119t.576.165t.56.211t.542.255t.52.297t.495.338q.24.178.466.376q.225.197.434.412t.401.445q.191.231.363.476t.325.503t.283.528q.131.269.24.549q.109.279.196.566M11.9 19.5H2.5v-5h8.1m5.15 2.75a2.25 2.25 0 0 1 4.5 0v1.25l.75 1.25h-6l.75-1.25Zm1.5 4.25h1.5m-4.25-7l7 7");
}

</style>
