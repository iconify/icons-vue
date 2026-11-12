<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mab_sh88u"/><path class="f05hkgr9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-sparkle-duotone" /></template>
<style>
.f05hkgr9l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3H4a1 1 0 0 0-1 1v3m14-4h3a1 1 0 0 1 1 1v3M3 17v3a1 1 0 0 0 1 1h3m10 0h3a1 1 0 0 0 1-1v-3M11 3h2m-2 18h2M3 11v2m18-2v2m-9-5c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.ft5dv1b6b {
  fill: none;
}

.mab_sh88u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 12c-2.005.002-3.998 1.995-4 4c-.002-2.005-1.995-3.998-4-4c2.005-.002 3.998-1.995 4-4c.002 2.005 1.995 3.998 4 4");
}

</style>
