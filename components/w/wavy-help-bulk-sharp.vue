<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ey4677bgx"/><path class="oidse6wjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-help-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ey4677bgx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.217 8.53c2.376 1.655 2.376 5.285 0 6.94c.617 2.786-1.961 5.364-4.747 4.747c-1.655 2.376-5.285 2.376-6.94 0c-2.786.617-5.364-1.961-4.747-4.747c-2.376-1.655-2.376-5.285 0-6.94c-.617-2.786 1.961-5.364 4.747-4.747c1.655-2.376 5.285-2.376 6.94 0c2.786-.617 5.364 1.961 4.747 4.747");
}

.oidse6wjy {
  d: path("M9 11a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 11a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
