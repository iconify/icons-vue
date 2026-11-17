<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o1cpw4bbn"/><path class="vcie4y7hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-connected-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o1cpw4bbn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.293 12.707l-6-6a1 1 0 0 1 0-1.414a5.2 5.2 0 0 1 1.735-1.152A5.2 5.2 0 0 1 15 3.757a5.23 5.23 0 0 1 3.707 1.536A5.23 5.23 0 0 1 20.243 9a5.2 5.2 0 0 1-.384 1.972a5.2 5.2 0 0 1-1.152 1.735a1 1 0 0 1-1.414 0M6.707 11.293l6 6a1 1 0 0 1 0 1.414a5.2 5.2 0 0 1-1.735 1.152A5.2 5.2 0 0 1 9 20.243a5.23 5.23 0 0 1-3.707-1.536A5.23 5.23 0 0 1 3.757 15a5.2 5.2 0 0 1 .384-1.972a5.2 5.2 0 0 1 1.152-1.735a1 1 0 0 1 1.414 0");
}

.vcie4y7hb {
  d: path("M20.293 2.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414-1.414Zm-11 7a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414Zm4 4a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414Zm-9.586 8.414a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 1.414Z");
}

</style>
