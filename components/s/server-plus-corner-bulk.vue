<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sowt4_0jd"/><path class="lxugqubzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-plus-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lxugqubzb {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM18 21a1 1 0 0 1-2 0v-3h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2h-3ZM7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

.sowt4_0jd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8 8v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1");
}

</style>
