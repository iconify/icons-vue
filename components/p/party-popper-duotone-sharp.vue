<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ob-gjobyw"/><path class="ykc-7hbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:party-popper-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ob-gjobyw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.702 10.057c.053.305.18.596.317.871c.249.497.563.961.9 1.402q.596.774 1.288 1.463q.689.692 1.463 1.288a9 9 0 0 0 1.402.9c.275.137.566.264.871.317l.741-.247a1.001 1.001 0 0 1 1.023 1.656c-.239.24-.534.416-.859.512a2.4 2.4 0 0 1-.639.099L3.316 21.949a1.001 1.001 0 0 1-1.265-1.265L5.682 9.791a2.4 2.4 0 0 1 .099-.639c.096-.325.272-.62.512-.859a.997.997 0 0 1 1.414 0c.268.268.361.664.242 1.023Z");
}

.ykc-7hbck {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9L3 21l12-4c-2 2-10-6-8-8m0 0c2-2 10 6 8 8S5 11 7 9m4-6v2m5 3l2-2m1 7h2M15 3h.01M21 9h-.01");
}

</style>
