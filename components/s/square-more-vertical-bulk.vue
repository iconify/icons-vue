<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="w0d5zzb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-more-vertical-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.w0d5zzb4m {
  d: path("M12.01 7a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
