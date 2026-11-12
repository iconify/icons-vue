<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z-5yhbcwi"/><path class="lldvpfbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-electricity-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lldvpfbik {
  d: path("M12 11h2a.998.998 0 0 1 .8 1.6l-3 4a1 1 0 0 1-1.6-1.2L12 13h-2a.998.998 0 0 1-.8-1.6l3-4a1 1 0 0 1 1.6 1.2Zm-7 0a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm16 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

.z-5yhbcwi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5Z");
}

</style>
