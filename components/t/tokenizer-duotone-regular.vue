<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="thz-qac8s"/><path class="twnn15b6d"/><path class="ub6op3wbj"/><path class="fnt0heb9z"/><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="zrdou8b0n"/><path class="uxy9sxbfx"/><path class="wgmfnvzml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tokenizer-duotone-regular" /></template>
<style>
.d223d_x9q {
  d: path("M3 12h6");
}

.fnt0heb9z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 19h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.thz-qac8s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.twnn15b6d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ub6op3wbj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.wgmfnvzml {
  d: path("M16 19h5");
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
