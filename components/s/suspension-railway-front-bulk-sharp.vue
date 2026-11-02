<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t6ljmhb7f"/><path class="kc-rtuyok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suspension-railway-front-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kc-rtuyok {
  d: path("M21 3a1 1 0 0 1 0 2h-5v4a1 1 0 0 1-2 0V5h-4v4a1 1 0 0 1-2 0V5H3a1 1 0 0 1 0-2ZM9.01 16a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Z");
}

.t6ljmhb7f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 20V9a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1m2-7h12v-3H6Z");
}

</style>
