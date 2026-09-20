<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ve--zpbav"/><path class="vcza2_uui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pencil-ruler-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vcza2_uui {
  d: path("M208 32h-48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h48a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 176h-48v-32h24a8 8 0 0 0 0-16h-24v-24h24a8 8 0 0 0 0-16h-24V96h24a8 8 0 0 0 0-16h-24V48h48zM77.66 26.34a8 8 0 0 0-11.32 0l-32 32A8 8 0 0 0 32 64v144a16 16 0 0 0 16 16h48a16 16 0 0 0 16-16V64a8 8 0 0 0-2.34-5.66ZM48 176V80h16v96Zm32-96h16v96H80Zm-8-36.69L92.69 64H51.31ZM48 208v-16h48v16Z");
}

.ve--zpbav {
  d: path("M40 184h64v24a8 8 0 0 1-8 8H48a8 8 0 0 1-8-8ZM208 40h-48a8 8 0 0 0-8 8v160a8 8 0 0 0 8 8h48a8 8 0 0 0 8-8V48a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
