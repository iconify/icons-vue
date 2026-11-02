<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pwjokzbwc"/><path class="k0zutvbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wine-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k0zutvbeq {
  d: path("M7 9h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m1 13a1 1 0 0 1 0-2h3v-5a1 1 0 0 1 2 0v5h3a1 1 0 0 1 0 2Z");
}

.pwjokzbwc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2h6c.4 0 .762.238.919.606c.612 1.427 1.191 2.879 1.607 4.376c.272.981.474 1.997.474 3.018a5.97 5.97 0 0 1-1.757 4.243A5.98 5.98 0 0 1 12 16a5.97 5.97 0 0 1-4.243-1.757A5.98 5.98 0 0 1 6 10c0-1.021.202-2.037.474-3.018c.416-1.497.995-2.949 1.607-4.376A1 1 0 0 1 9 2");
}

</style>
