<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b-osb3b-f"/><path class="ey4y9ubwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-duotone" /></template>
<style>
.b-osb3b-f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.293 3.293C17.008 2.578 17.961 2 19 2h2a1 1 0 0 1 1 1v2c0 1.039-.578 1.992-1.293 2.707l-10 10a1 1 0 0 1-1.414 0l-3-3a.997.997 0 0 1 0-1.414Z");
}

.ey4y9ubwa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L17 4c.64-.64 1.36-1 2-1h2v2c0 .64-.36 1.36-1 2L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

.ft5dv1b6b {
  fill: none;
}

</style>
