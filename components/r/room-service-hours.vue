<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o-t1c2ycj"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:room-service-hours" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.o-t1c2ycj {
  d: path("M3.5 15q0-.184.009-.368t.027-.367t.045-.365t.063-.363t.081-.359t.098-.355t.115-.35t.133-.343t.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29t.241-.279q.124-.136.254-.266t.266-.254q.137-.124.279-.241t.29-.226t.301-.212t.311-.197t.321-.181t.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027T11 7.5q.271 0 .541.02q.27.019.538.058t.532.097t.524.135t.513.173t.499.209q.245.114.482.245t.464.278t.443.312t.418.342q.204.179.393.372t.366.399q.175.207.335.425t.304.448q.144.229.271.468t.237.487M11 4.5v3M2.5 15h10.2m2.05 3a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
