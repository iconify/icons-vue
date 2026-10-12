<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ufgqyma-f"/><path class="yk6-nmpqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mailbox-parcel-sharp" /></template>
<style>
.ufgqyma-f {
  d: path("M5.25 20.25V9.5a6.75 6.75 0 0 1 13.5 0v11.75H5.25zm3.5-11.5h6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yk6-nmpqs {
  d: path("M9 12.75h6v5H9zm3 0v1.75");
}

</style>
