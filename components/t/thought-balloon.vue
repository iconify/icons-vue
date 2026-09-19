<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="translate(.11 5.498)" class="dblf6lbtm"><ellipse class="xw4599bcq"/><ellipse class="sa9z_6ufu"/><ellipse class="xa0rkbccj"/><ellipse class="hqgu-1b9d"/><ellipse class="bzgnawbpu"/><ellipse class="c1m5zsbbl"/><ellipse class="vubkpohjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:thought-balloon" /></template>
<style>
.bzgnawbpu {
  cx: 34.851px;
  cy: 12.92px;
  rx: 18.06px;
  ry: 9.916px;
}

.c1m5zsbbl {
  cx: 33.618px;
  cy: 29.778px;
  rx: 18.06px;
  ry: 9.915px;
}

.dblf6lbtm {
  fill: var(--svg-color--97d8ea, #97d8ea);
}

.hqgu-1b9d {
  cx: 34.851px;
  cy: 13.792px;
  rx: 23.574px;
  ry: 14.02px;
}

.sa9z_6ufu {
  cx: 6.676px;
  cy: 51.49px;
  rx: 2.899px;
  ry: 2.24px;
}

.vubkpohjx {
  cx: 46.721px;
  cy: 27.537px;
  rx: 17.14px;
  ry: 9.444px;
}

.xa0rkbccj {
  cx: 16.794px;
  cy: 24.828px;
  rx: 16.824px;
  ry: 12.258px;
}

.xw4599bcq {
  cx: 14.177px;
  cy: 44.842px;
  rx: 4.602px;
  ry: 3.746px;
}

</style>
