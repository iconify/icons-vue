<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jr6l_acwa"/><path class="ss3d290uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-decrease-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jr6l_acwa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 11h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

.ss3d290uf {
  d: path("M8 4h5a1 1 0 0 1 0 2H9v13a1 1 0 0 1-2 0V6H3a1 1 0 0 1 0-2Z");
}

</style>
