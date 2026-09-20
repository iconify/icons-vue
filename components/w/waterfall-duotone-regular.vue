<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i7z0vob4i"/><path class="hmylfkbub"/><path class="q5fdyummg"/><path class="jp1ucxmwc"/><path class="vubu-cfsw"/><path class="xf07dvr8m"/><path class="tr_jskylo"/><path class="hxoe7gx5p"/><path class="e0001wg8c"/><path class="y_21nobec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waterfall-duotone-regular" /></template>
<style>
.e0001wg8c {
  d: path("M17 5v12");
}

.hmylfkbub {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.i7z0vob4i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jp1ucxmwc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5fdyummg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tr_jskylo {
  d: path("M7 5v12");
}

.vubu-cfsw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.y_21nobec {
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
