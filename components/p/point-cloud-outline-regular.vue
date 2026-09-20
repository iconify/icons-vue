<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lu0ovacdk"/><path class="oq9ztqbxu"/><path class="fglxyivky"/><path class="lx3jidcux"/><path class="k-jt90-vx"/><path class="tr__z6b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:point-cloud-outline-regular" /></template>
<style>
.fglxyivky {
  d: path("M18 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k-jt90-vx {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lu0ovacdk {
  d: path("M4 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lx3jidcux {
  d: path("M4 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oq9ztqbxu {
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.tr__z6b9j {
  d: path("M18 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
