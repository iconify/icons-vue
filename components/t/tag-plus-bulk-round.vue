<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tlaao6rpw"/><path class="zz9dj1bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tlaao6rpw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 8v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8c0-1.039.578-1.992 1.293-2.707l2-2C8.008 2.578 8.961 2 10 2h4c1.039 0 1.992.578 2.707 1.293l2 2C19.422 6.008 20 6.961 20 8");
}

.zz9dj1bep {
  d: path("M11 5h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2m2 7v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
