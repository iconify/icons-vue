<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s6795lb_y"/><path class="gxmqsnbdz"/><path class="sg3hqpbqs"/><path class="glg1b_buf"/><path class="fnbgpcbhf"/><path class="wlpa9-b1f"/><path class="aut8y9hmn"/><path class="k6x6uv-ap"/><path class="h2va4xb2x"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:museum-duotone-regular" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.glg1b_buf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gxmqsnbdz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2va4xb2x {
  d: path("M17 11v8");
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6795lb_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 11 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sg3hqpbqs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlpa9-b1f {
  d: path("m5 11 7 -7 7 7");
}

</style>
