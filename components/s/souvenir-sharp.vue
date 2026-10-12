<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="iejqtrbgm"/><path class="sa495vhbc"/><path class="tx-15vb7y"/><path class="ro33jp0je"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:souvenir-sharp" /></template>
<style>
.iejqtrbgm {
  cx: 12px;
  cy: 9.75px;
  r: 7px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ro33jp0je {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 16.75h9.5l.36.93l1.03 2.64l.36.93H5l.36-.93l1.03-2.64l.36-.93z");
}

.sa495vhbc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.31 6.93l2.38 5.14l.31.68H9l.31-.68l2.38-5.14l.31-.68z");
}

.tx-15vb7y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 8.5h.01M16 7.25h.01m.74 2.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
