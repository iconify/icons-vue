<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="urw8q1bht"/><path class="cgsegub5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-scorpio-bulk" /></template>
<style>
.cgsegub5l {
  d: path("M5 2.764a3 3 0 0 1 4 0a3 3 0 0 1 3.225-.502A3 3 0 0 1 14 5v10a2 2 0 0 0 2 2a1 1 0 0 1 0 2a3.98 3.98 0 0 1-2.828-1.172A3.98 3.98 0 0 1 12 15V5a1 1 0 0 0-2 0v10a1 1 0 0 1-2 0V5a1 1 0 0 0-2 0v10a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1a1 1 0 0 1 0-2c.74 0 1.45.27 2 .764");
}

.cuyn6tgcc {
  fill: currentColor;
}

.urw8q1bht {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.707 17.293a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L18.586 19H16a1 1 0 0 1 0-2h2.586l-1.293-1.293a1 1 0 0 1 1.414-1.414Z");
}

</style>
