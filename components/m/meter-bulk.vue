<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="njdad_b8c"/><path class="hnn6y9d9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hnn6y9d9o {
  d: path("M9 4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM7 6h10a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m0 2v3h2V8Zm4 3h2V8h-2Zm4-3v3h2V8Zm-7 9h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

.njdad_b8c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
