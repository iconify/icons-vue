<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mp-ry4jnc"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

.mp-ry4jnc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.047 14.805L7.292 2.049Q7.644 1.999 8 2h8a5 5 0 0 1 5 5v3c0 1.645-.302 3.291-.953 4.805M4.464 3.464l13.991 13.991c-1.586 1.989-3.741 3.433-6.049 4.459a1 1 0 0 1-.812 0c-2.316-1.03-4.478-2.48-6.065-4.48C3.824 15.283 3 12.737 3 10V7c0-1.33.522-2.597 1.464-3.536");
}

</style>
