<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a513_lbdu"/><path class="s6450lbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-bulk-sharp" /></template>
<style>
.a513_lbdu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.976 7.782l-6.933 6.932A17 17 0 0 1 2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5q.03.073.048.153m-4.997 9.239l4.228-4.228L13 14.586l2.293-2.293a1 1 0 0 1 1.078-.221l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2a16.95 16.95 0 0 1-12.021-4.979");
}

.cuyn6tgcc {
  fill: currentColor;
}

.s6450lbyw {
  d: path("m1.293 21.293l20-20a.999.999 0 1 1 1.414 1.414l-20 20a.999.999 0 1 1-1.414-1.414");
}

</style>
