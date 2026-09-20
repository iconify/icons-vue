<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ysl8rybjy"/><path class="n5li845gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wall-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n5li845gk {
  d: path("M224 48H32a8 8 0 0 0-8 8v144a8 8 0 0 0 8 8h192a8 8 0 0 0 8-8V56a8 8 0 0 0-8-8M88 144v-32h80v32Zm-48 0v-32h32v32Zm144-32h32v32h-32Zm32-16h-80V64h80Zm-96-32v32H40V64Zm-80 96h80v32H40Zm96 32v-32h80v32Z");
}

.ysl8rybjy {
  d: path("M128 104H32V56h96Zm48 0v48h-48v48h96v-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
