<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="td1rq2hbd"/><path class="hhlu2ixlu"/><g class="eyuj09bzi"><circle class="k7muvkgfc"/><path class="isueyvx-s"/></g><g class="ed4r-5bxj"><circle class="j_-5nwtci"/><circle class="y-r250mgy"/></g><g class="eyuj09bzi"><circle class="p8sowr01w"/><path class="zj_nljm9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:waxing-gibbous-moon" /></template>
<style>
.ed4r-5bxj {
  fill: var(--svg-color--4f6977, #4f6977);
}

.eyuj09bzi {
  fill: var(--svg-color--e0cf35, #e0cf35);
}

.hhlu2ixlu {
  fill: var(--svg-color--405866, #405866);
  d: path("M18.281 3.397C7.571 8.534.161 19.447.161 32.111c0 14.497 9.689 26.71 22.938 30.571c-10.963-10.539-19.1-39.15-4.816-59.29");
}

.isueyvx-s {
  d: path("M41.921 24.477a3.918 3.918 0 0 1-7.833 0a3.917 3.917 0 0 1 7.833 0");
}

.j_-5nwtci {
  cx: 5.998px;
  cy: 36.526px;
  r: 3.844px;
}

.k7muvkgfc {
  cx: 29.339px;
  cy: 53px;
  r: 9.222px;
}

.p8sowr01w {
  cx: 17.561px;
  cy: 19.647px;
  r: 3.431px;
}

.td1rq2hbd {
  cx: 32.02px;
  cy: 32.11px;
  r: 31.863px;
  fill: var(--svg-color--f5eb35, #f5eb35);
}

.y-r250mgy {
  cx: 6.344px;
  cy: 18.911px;
  r: 2.194px;
}

.zj_nljm9s {
  d: path("M47.745 11.07a4.83 4.83 0 0 1-4.833 4.83a4.832 4.832 0 1 1 4.833-4.83");
}

</style>
