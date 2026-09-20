<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v-xzyqe3f"/><path class="jmolxjtwy"/><path class="j6hwip25h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scalpel-duotone-regular" /></template>
<style>
.j6hwip25h {
  d: path("m13 12 2 2");
}

.jmolxjtwy {
  d: path("m4 20 8 -8 4 -4 3 3 -4 4 -5 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-xzyqe3f {
  fill: currentColor;
  d: path("m4 20 8 -8 4 -4 3 3 -4 4 -5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
