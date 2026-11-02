<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ig83ifhpq"/><path class="urgjmybtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ig83ifhpq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m11 15H3a1 1 0 0 1-1-1a6.9 6.9 0 0 1 .551-2.725A6.9 6.9 0 0 1 4.05 16.05A6.97 6.97 0 0 1 9 14c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-1 1");
}

.urgjmybtl {
  d: path("M15 4a1 1 0 0 1 0-2c2.011 0 3.826 1.2 4.607 3.053a5 5 0 0 1-.44 4.711A5 5 0 0 1 15 12a1 1 0 0 1 0-2a3 3 0 1 0 0-6M2 21a7 7 0 1 1 14 0a1 1 0 0 1-2 0a5.001 5.001 0 0 0-10 0a1 1 0 0 1-2 0m13-6a1 1 0 0 1 1-1c.834 0 1.657.197 2.399.58a6.1 6.1 0 0 1 1.905 1.537a7.1 7.1 0 0 1 1.246 2.215A7.9 7.9 0 0 1 22 21a1 1 0 0 1-2 0c0-1.29-.4-2.603-1.233-3.603C18.073 16.565 17.093 16 16 16a1 1 0 0 1-1-1");
}

</style>
