<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dtro9rbwa"/><path class="o70xbqbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-info-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dtro9rbwa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.874 1.514l10 18A1 1 0 0 1 22 21H2a1 1 0 0 1-.874-1.486l10-18a1 1 0 0 1 1.748 0");
}

.o70xbqbae {
  d: path("M12 9h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m1 4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
