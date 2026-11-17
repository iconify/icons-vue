<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d5p-0mrlj"/><path class="znwteqb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-map-pin-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d5p-0mrlj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 9a1 1 0 0 1 0 2a5 5 0 0 0-4.905 4.028l-.677 3.416a1 1 0 0 1-.198.429L9.655 20.84A1.35 1.35 0 0 1 7.25 20v-5H4a1.483 1.483 0 0 1-1.16-2.405l7.505-9.435A1.35 1.35 0 0 1 12.75 4v5Z");
}

.znwteqb7e {
  d: path("M15.184 20.777C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m2.523-5.484a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414");
}

</style>
