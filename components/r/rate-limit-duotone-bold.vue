<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jqzkbwbya"/><path class="wc2iww91l"/><path class="uwclokbjs"/><path class="uyr1302ms"/><path class="tit913_ho"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="h5uycs4sy"/><path class="wp75hkmty"/><path class="y2lgilb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rate-limit-duotone-bold" /></template>
<style>
.h5uycs4sy {
  d: path("M2 16h8");
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.jqzkbwbya {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o0-3vqblf {
  d: path("M2 8h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tit913_ho {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uwclokbjs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uyr1302ms {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wc2iww91l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wp75hkmty {
  d: path("M11 7v10");
}

.y2lgilb0y {
  d: path("M13 12h9");
}

</style>
