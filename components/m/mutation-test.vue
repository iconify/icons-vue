<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zt92tbfeq"/><path class="czk20gbmv"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mutation-test" /></template>
<style>
.czk20gbmv {
  fill: currentColor;
  d: path("M8 8.25h1.75v3.5H8a1.75 1.75 0 0 1 0-3.5Z");
}

.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zt92tbfeq {
  d: path("M2.5 2.5h1V15q0 .11.005.221q.006.11.017.22q.01.11.027.219q.016.11.037.218q.022.108.049.215q.027.108.059.213q.032.106.069.21t.08.206q.042.102.089.202t.099.197t.109.192t.118.187q.062.092.128.181q.065.088.135.174t.145.167q.074.082.152.16t.16.152t.167.145q.086.07.174.135q.089.066.181.128q.092.061.187.118q.094.057.192.109q.097.052.197.099t.202.089q.102.043.206.08t.21.069t.213.059t.215.049t.218.037q.109.016.219.027t.22.017q.111.005.221.005q.425 0 .843-.08q.417-.079.813-.236t.754-.384q.359-.227.669-.518m1.122-1.669q.299-.779.299-1.613V2.5h1");
}

</style>
