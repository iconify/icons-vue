<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i1u9r6bcs"/><path class="gcs_0llox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-cloud-sharp" /></template>
<style>
.gcs_0llox {
  d: path("M9 13.5h6v4H9zm1.5 0V11h3v2.5");
}

.i1u9r6bcs {
  d: path("M6.75 19.85a4 4 0 0 1-.55-7.96a5.75 5.75 0 0 1 10.65-1.39a4.5 4.5 0 0 1-.6 9.35Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
