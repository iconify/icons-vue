<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="cjx7a2bdd"/><path class="im38brk4q"/><path class="n_nmc0bnb"/><path class="xgkt50b4f"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="uxyzhxvwz"/><path class="ajea6vpsn"/><path class="tuynf1bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spacing-duotone-regular" /></template>
<style>
.ajea6vpsn {
  d: path("m9 10 -2 2 2 2");
}

.cjx7a2bdd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.im38brk4q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_nmc0bnb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.tuynf1bdi {
  d: path("m15 10 2 2 -2 2");
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

.ws1d0fbts {
  d: path("M20 4v16");
}

.xgkt50b4f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
