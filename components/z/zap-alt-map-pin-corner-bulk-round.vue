<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f86_bubgx"/><path class="znwteqb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-map-pin-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f86_bubgx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.394 9a1 1 0 0 1 .516 1.857a5.9 5.9 0 0 0-1.887 1.792a5.9 5.9 0 0 0-.951 2.421a1 1 0 0 1-.28.553l-4.671 4.67a1.582 1.582 0 0 1-2.663-1.462l1.24-5.584A.202.202 0 0 0 4.5 13a1.974 1.974 0 0 1-1.805-2.777l2.863-6.441A3 3 0 0 1 8.3 2H12a2.162 2.162 0 0 1 1.876 3.233L11.861 8.76A.16.16 0 0 0 12 9Z");
}

.znwteqb7e {
  d: path("M15.184 20.777C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m2.523-5.484a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414");
}

</style>
