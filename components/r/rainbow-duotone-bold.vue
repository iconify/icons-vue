<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yt70p9btb"/><path class="i260mgbeq"/><path class="jqwxvo9pv"/><path class="kr5tlbbsn"/><path class="srzgk7jml"/><path class="vvh_i7bfp"/><path class="tcbtlrbob"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rainbow-duotone-bold" /></template>
<style>
.i260mgbeq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 17a6.5 6.5 0 0 1 13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.jqwxvo9pv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kr5tlbbsn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.tcbtlrbob {
  d: path("M8 17a4 4 0 0 1 8 0");
}

.vvh_i7bfp {
  d: path("M5.5 17a6.5 6.5 0 0 1 13 0");
}

.yt70p9btb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
