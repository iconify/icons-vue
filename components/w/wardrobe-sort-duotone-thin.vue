<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ooa16o-xd"/><path class="p8buz1t1r"/><path class="vniunubej"/><path class="g1gntlbfm"/><path class="rwge04jxw"/><path class="g7akhoeoj"/><path class="wlp3ibbib"/><path class="qrqk-5btd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wardrobe-sort-duotone-thin" /></template>
<style>
.g1gntlbfm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7akhoeoj {
  d: path("m6 13 6 -6 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ooa16o-xd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p8buz1t1r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrqk-5btd {
  d: path("m9 17 3 3 3 -3");
}

.rwge04jxw {
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
}

.vniunubej {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
