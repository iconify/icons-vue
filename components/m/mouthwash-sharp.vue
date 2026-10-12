<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hm_7vba3a"/><path class="w9fye5bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mouthwash-sharp" /></template>
<style>
.hm_7vba3a {
  d: path("M8.75 2.75h6.5v3.5h-6.5zm1.75 3.5h4.25V8.5l.95.81l1.6 1.38l.95.81v9.75H5.75V11.5l.95-.81l1.6-1.38l.95-.81V6.25z");
}

.w9fye5bvt {
  d: path("M5.75 15.5c2-1 4.25-1 6.25 0s4.25 1 6.25 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
