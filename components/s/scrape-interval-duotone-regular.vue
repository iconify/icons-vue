<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="k_7z1bcnp"/><path class="irk9zbcmx"/><path class="c39r_abdo"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f26bn-hui"/><path class="l517yxbln"/><path class="dti01qb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scrape-interval-duotone-regular" /></template>
<style>
.c39r_abdo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dti01qb8s {
  d: path("M16 9v6");
}

.f26bn-hui {
  d: path("M8 9v6");
}

.irk9zbcmx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k_7z1bcnp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
