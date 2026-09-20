<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="he5ikxbaq"/><path class="digwvcbca"/><path class="ayn__6bdt"/><path class="f275eobml"/><path class="ckawxab4i"/><path class="d8abqfbpc"/><path class="rdv9wsbxa"/><path class="u78lc2bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shade-duotone-regular" /></template>
<style>
.ayn__6bdt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ckawxab4i {
  d: path("m4 11 8 -8 8 8");
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.digwvcbca {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f275eobml {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.he5ikxbaq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rdv9wsbxa {
  d: path("M12 11v9");
}

.u78lc2bnx {
  d: path("M6 20h12");
}

</style>
