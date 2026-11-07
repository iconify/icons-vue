<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="df4o7fpul"/><path class="pfz45v9bw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-zap-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.df4o7fpul {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

.pfz45v9bw {
  d: path("M7 7a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm10 4a1 1 0 0 1 .857 1.514l-3 5a1 1 0 0 1-1.371.343a1 1 0 0 1-.343-1.371L19.234 13H17a1 1 0 0 1-.857-1.514l3-5a.998.998 0 0 1 1.731.029a1 1 0 0 1-.017.999L18.766 11ZM9 21a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
