<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ygqlu6xwg"/><path class="lldvpfbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-electricity-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lldvpfbik {
  d: path("M12 11h2a.998.998 0 0 1 .8 1.6l-3 4a1 1 0 0 1-1.6-1.2L12 13h-2a.998.998 0 0 1-.8-1.6l3-4a1 1 0 0 1 1.6 1.2Zm-7 0a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm16 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

.ygqlu6xwg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

</style>
