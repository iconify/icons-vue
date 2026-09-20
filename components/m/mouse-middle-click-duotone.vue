<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="dziq8_b6j"/><path class="igh4i197x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:mouse-middle-click-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dziq8_b6j {
  d: path("M144 88v48a8 8 0 0 1-8 8h-16a8 8 0 0 1-8-8V88a8 8 0 0 1 8-8h16a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.igh4i197x {
  d: path("M144 16h-32a64.07 64.07 0 0 0-64 64v96a64.07 64.07 0 0 0 64 64h32a64.07 64.07 0 0 0 64-64V80a64.07 64.07 0 0 0-64-64m48 64v24h-40V88a16 16 0 0 0-16-16V32h8a48.05 48.05 0 0 1 48 48m-56 56h-16V88h16v23.9a.5.5 0 0 0 0 .2ZM112 32h8v40a16 16 0 0 0-16 16v16H64V80a48.05 48.05 0 0 1 48-48m32 192h-32a48.05 48.05 0 0 1-48-48v-56h40v16a16 16 0 0 0 16 16h16a16 16 0 0 0 16-16v-16h40v56a48.05 48.05 0 0 1-48 48");
}

</style>
