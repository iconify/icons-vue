<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6ei3vbab"/><path class="twmfkyr5z"/><path class="chq5kftbx"/><path class="wfd9yacqd"/><path class="srzgk7jml"/><path class="vvh_i7bfp"/><path class="tcbtlrbob"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rainbow-duotone-regular" /></template>
<style>
.chq5kftbx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 17a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.tcbtlrbob {
  d: path("M8 17a4 4 0 0 1 8 0");
}

.twmfkyr5z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 17a6.5 6.5 0 0 1 13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vvh_i7bfp {
  d: path("M5.5 17a6.5 6.5 0 0 1 13 0");
}

.wfd9yacqd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x6ei3vbab {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
