<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="apwo9exbc"/><path class="s-j14r68l"/><path class="o3r8utdvv"/><path class="v5d2b2g6o"/><path class="rwge04jxw"/><path class="g7akhoeoj"/><path class="wlp3ibbib"/><path class="qrqk-5btd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wardrobe-sort-duotone-regular" /></template>
<style>
.apwo9exbc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7akhoeoj {
  d: path("m6 13 6 -6 6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o3r8utdvv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrqk-5btd {
  d: path("m9 17 3 3 3 -3");
}

.rwge04jxw {
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
}

.s-j14r68l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5d2b2g6o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
