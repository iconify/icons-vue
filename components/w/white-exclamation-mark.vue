<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="l_kccubev"><path class="cuyyezbxs"/><ellipse class="o-hj8qbbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:white-exclamation-mark" /></template>
<style>
.cuyyezbxs {
  d: path("M37 42.4H27L23 2h18z");
}

.l_kccubev {
  fill: var(--svg-color--a6aeb0, #a6aeb0);
}

.o-hj8qbbo {
  cx: 32px;
  cy: 54.4px;
  rx: 7.7px;
  ry: 7.6px;
}

</style>
