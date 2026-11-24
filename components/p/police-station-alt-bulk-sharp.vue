<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gd-4pggfu"/><path class="kv1vfpbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gd-4pggfu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.kv1vfpbxn {
  d: path("M9 5h6a1 1 0 0 1 1 1v2.625c-.001 2.409-1.475 4.097-3.594 5.039a1 1 0 0 1-.812 0C9.475 12.722 8.001 11.034 8 8.625V6a1 1 0 0 1 1-1m12 17H3a1 1 0 0 1 0-2h6v-3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3h6a1 1 0 0 1 0 2m-8-2v-2h-2v2Z");
}

</style>
