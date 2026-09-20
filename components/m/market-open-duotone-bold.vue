<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zu6uukbhb"/><path class="kr5tlbbsn"/><path class="k2kht2b4d"/><path class="p1kqe-e4e"/><path class="xgrr24b5t"/><path class="ja-d7-b4a"/><path class="ic_pehd5a"/><path class="gyu499fcn"/><path class="k4y331wag"/><path class="xdvtlk8qz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:market-open-duotone-bold" /></template>
<style>
.gyu499fcn {
  d: path("M12 6v2.5");
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.ja-d7-b4a {
  d: path("M6 17a6 6 0 0 1 12 0");
}

.k2kht2b4d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4y331wag {
  d: path("m4.5 9.5 2 2");
}

.kr5tlbbsn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p1kqe-e4e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4.5 9.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xdvtlk8qz {
  d: path("m19.5 9.5 -2 2");
}

.xgrr24b5t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19.5 9.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zu6uukbhb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 17a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
