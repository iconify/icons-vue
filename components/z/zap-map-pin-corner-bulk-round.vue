<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ne5-w4b3f"/><path class="znwteqb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-map-pin-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ne5-w4b3f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 9a1 1 0 0 1 0 2a5 5 0 0 0-4.905 4.028l-.677 3.416a1 1 0 0 1-.198.429l-.942 1.184A1.699 1.699 0 0 1 7.25 19v-3a.997.997 0 0 0-1-1H5a1.966 1.966 0 0 1-1.538-3.188l6.26-7.869A1.697 1.697 0 0 1 12.75 5v3a.997.997 0 0 0 1 1Z");
}

.znwteqb7e {
  d: path("M15.184 20.777C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m2.523-5.484a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414");
}

</style>
