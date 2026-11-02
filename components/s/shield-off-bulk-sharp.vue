<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wdhbyvb8h"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

.wdhbyvb8h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.498 13.256L7.243 2H20a1 1 0 0 1 1 1v7c0 1.645-.302 3.291-.953 4.805ZM3.293 2.293l15.162 15.162c-1.586 1.989-3.741 3.433-6.049 4.459a1 1 0 0 1-.812 0c-2.316-1.03-4.478-2.48-6.065-4.48C3.824 15.283 3 12.737 3 10V3c0-.265.105-.52.293-.707");
}

</style>
