<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uykxl6bsn"/><path class="eaysgub_v"/><path class="z_smtp8xa"/><path class="atcmxjbma"/><path class="p4idz7btn"/><path class="h6srt4n9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-check-duotone-regular" /></template>
<style>
.atcmxjbma {
  d: path("M4 5h12");
}

.eaysgub_v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h6srt4n9a {
  d: path("m14 15 3 3 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4idz7btn {
  d: path("M10 5v10");
}

.uykxl6bsn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z_smtp8xa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 15 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
