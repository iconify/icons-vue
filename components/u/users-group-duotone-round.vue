<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ri9ngmbky"/><path class="a_rc_bytf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-group-duotone-round" /></template>
<style>
.a_rc_bytf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0M7 21c0-2.21 2.239-4 5-4s5 1.79 5 4M8 5a2.236 2.236 0 1 0-2 4m10-4a2.236 2.236 0 1 1 2 4M3 17c0-1.657 1.79-3 4-3m10 0c2.21 0 4 1.343 4 3");
}

.ft5dv1b6b {
  fill: none;
}

.ri9ngmbky {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.315 8.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114M17 22H7a1 1 0 0 1-1-1c0-.706.174-1.402.509-2.024a5.1 5.1 0 0 1 1.331-1.585C9.009 16.456 10.513 16 12 16s2.991.456 4.16 1.391a5.1 5.1 0 0 1 1.331 1.585c.335.622.509 1.318.509 2.024a1 1 0 0 1-1 1");
}

</style>
