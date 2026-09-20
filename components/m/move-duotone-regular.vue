<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw099db1h"/><path class="u-kmlrghs"/><path class="ic718vbfc"/><path class="v5d2b2g6o"/><path class="mkb129lfs"/><path class="gmcwnnbyg"/><path class="r7xk8o29f"/><path class="sxlwlmkmh"/><path class="t407nkbfi"/><path class="qrqk-5btd"/><path class="cu_n5qbwp"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:move-duotone-regular" /></template>
<style>
.cu_n5qbwp {
  d: path("m7 9 -3 3 3 3");
}

.gmcwnnbyg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ic718vbfc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.mkb129lfs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 9 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrqk-5btd {
  d: path("m9 17 3 3 3 -3");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.t407nkbfi {
  d: path("m9 7 3 -3 3 3");
}

.u-kmlrghs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uw099db1h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5d2b2g6o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
