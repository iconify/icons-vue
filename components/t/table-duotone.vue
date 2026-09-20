<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="j98gnfblg"/><path class="cx736y5fz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:table-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cx736y5fz {
  d: path("M224 48H32a8 8 0 0 0-8 8v136a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a8 8 0 0 0-8-8M40 112h40v32H40Zm56 0h120v32H96Zm120-48v32H40V64ZM40 160h40v32H40Zm176 32H96v-32h120z");
}

.j98gnfblg {
  d: path("M88 104v96H32v-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
