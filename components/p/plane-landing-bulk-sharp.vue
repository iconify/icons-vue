<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bp71jcbek"/><path class="fjmgsib9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-bulk-sharp" /></template>
<style>
.bp71jcbek {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.707 11.293c1.536 1.536 2.951 3.462 1 5.414c-.692.692-1.538 1.096-2.528.899c-1.102-.221-2.116-1.128-2.886-1.899l-1.636-1.636l-5.493.915a1 1 0 0 1-.871-.279l-1-1A.998.998 0 0 1 4.4 12.2l3.332-2.499L7.382 9H6a1 1 0 0 1-.707-.293l-1-1a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 0l1 1A1 1 0 0 1 11 4v1.382l.701.35L14.2 2.4a.998.998 0 0 1 1.507-.107l1 1a1 1 0 0 1 .279.871l-.915 5.493Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fjmgsib9m {
  d: path("M3 20h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
