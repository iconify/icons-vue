<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vuxb4yb3s"/><path class="znwteqb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-map-pin-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vuxb4yb3s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.394 9a1 1 0 0 1 .516 1.857a5.9 5.9 0 0 0-1.887 1.792a5.9 5.9 0 0 0-.951 2.421a1 1 0 0 1-.28.553l-6.085 6.084a1 1 0 0 1-1.683-.924L4.753 13H3a1 1 0 0 1-.914-1.406l4-9C6.247 2.233 6.605 2 7 2h7a1 1 0 0 1 .868 1.496L11.723 9Z");
}

.znwteqb7e {
  d: path("M15.184 20.777C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m2.523-5.484a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414");
}

</style>
