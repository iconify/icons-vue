<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d-48k2f0w"/><path class="s6450lbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d-48k2f0w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.207 12.793l-4.228 4.228A16.95 16.95 0 0 1 2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11Zm-1.2 5.443l6.211-6.212a1 1 0 0 1 .153.048l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2a17 17 0 0 1-9.714-3.043Z");
}

.s6450lbyw {
  d: path("m1.293 21.293l20-20a.999.999 0 1 1 1.414 1.414l-20 20a.999.999 0 1 1-1.414-1.414");
}

</style>
