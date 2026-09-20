<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b0hkzgbgd"/><path class="wuk2mlziz"/><path class="iwjnwtbxd"/><path class="cta_b6xgu"/><path class="yvxn-ueef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:workspace-share-outline-regular" /></template>
<style>
.b0hkzgbgd {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.cta_b6xgu {
  d: path("M14.5 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iwjnwtbxd {
  d: path("M7.5 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wuk2mlziz {
  d: path("M7 19h10");
}

.yvxn-ueef {
  d: path("M9.5 10h5");
}

</style>
