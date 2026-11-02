<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ifc9x9b7z"/><path class="yb-9l7bqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ifc9x9b7z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 14a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.yb-9l7bqm {
  d: path("M9 12V8.38a3.828 3.828 0 0 1 5.601-5.189A3.83 3.83 0 0 1 15 8.38V12a1 1 0 0 1-2 0V8c0-.265.105-.52.293-.707A1.827 1.827 0 1 0 10.172 6c-.001.485.191.951.535 1.293A1 1 0 0 1 11 8v4a1 1 0 0 1-2 0M5 22a1 1 0 0 1 0-2h14a1 1 0 0 1 0 2Z");
}

</style>
