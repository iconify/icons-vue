<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ggmordb-b"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ggmordb-b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.047 14.805L7.243 2H18a3 3 0 0 1 3 3v5c0 1.645-.302 3.291-.953 4.805M3.879 2.879l14.576 14.576c-1.586 1.989-3.741 3.433-6.049 4.459a1 1 0 0 1-.812 0c-2.316-1.03-4.478-2.48-6.065-4.48C3.824 15.283 3 12.737 3 10V5c0-.797.314-1.558.879-2.121");
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
