<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="keqm5j6fz"/><path class="z6vskkt2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:onion-sharp" /></template>
<style>
.keqm5j6fz {
  d: path("m12 2.75l.708 2.479L14.75 6.25c3.25 1.5 5 4 5 7c0 3.5-3.5 5.5-7.75 5.5s-7.75-2-7.75-5.5c0-3 1.75-5.5 5-7l2.042-1.021z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6vskkt2q {
  d: path("M10 9c-2 1.4-2.75 2.75-2.75 4.25v1.523l1 1.077M14 9c2 1.4 2.75 2.75 2.75 4.25v1.523l-1 1.077M12 18.75v2.5M9.25 18.5l-1 2.25m6.5-2.25l1 2.25");
}

</style>
