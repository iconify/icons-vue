<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gm2kcpb5y"/><path class="ebkakui0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sparkles-alt-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ebkakui0m {
  d: path("M4 3a1 1 0 0 1 2 0c0 .449.551 1 1 1a1 1 0 0 1 0 2c-.449 0-1 .551-1 1a1 1 0 0 1-2 0c0-.449-.551-1-1-1a1 1 0 0 1 0-2c.449 0 1-.551 1-1m12 0a1 1 0 0 1 2 0q0 1.477.087 2.06c.027.184.075.5.214.639s.455.187.639.214Q19.523 6 21 6a1 1 0 0 1 0 2q-1.477 0-2.06.087c-.184.027-.5.075-.639.214s-.187.455-.214.639Q18 9.523 18 11a1 1 0 0 1-2 0q0-1.477-.087-2.06c-.027-.184-.075-.5-.214-.639s-.455-.187-.639-.214Q14.477 8 13 8a1 1 0 0 1 0-2q1.477 0 2.06-.087c.184-.027.5-.075.639-.214s.187-.455.214-.639Q16 4.477 16 3");
}

.gm2kcpb5y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 9a1 1 0 0 1 2 0c0 .617.162 1.223.422 1.78C11.21 12.468 13.073 14 15 14a1 1 0 0 1 0 2c-1.291 0-2.524.688-3.418 1.582a5.7 5.7 0 0 0-1.16 1.638c-.26.557-.422 1.163-.422 1.78a1 1 0 0 1-2 0c0-.617-.162-1.223-.422-1.78a5.7 5.7 0 0 0-1.16-1.638a5.7 5.7 0 0 0-1.638-1.16C4.223 16.162 3.617 16 3 16a1 1 0 0 1 0-2c2.451-.001 4.999-2.549 5-5");
}

</style>
