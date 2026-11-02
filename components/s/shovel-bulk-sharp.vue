<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lnc8dda3k"/><path class="g8zp34bpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g8zp34bpo {
  d: path("m15.707 4.293l2 1.999v.001l2 2a.999.999 0 1 1-1.414 1.414L17 8.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414L15.586 7l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.lnc8dda3k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.707 15.293a1 1 0 0 1 0 1.414l-2 2A1 1 0 0 1 12 19H6a1 1 0 0 1-1-1v-6c0-.265.105-.52.293-.707l2-2a1 1 0 0 1 1.414 0Z");
}

</style>
