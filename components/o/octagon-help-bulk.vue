<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uutrwzg_g"/><path class="ybi_gbb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-help-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uutrwzg_g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2h3c1.039 0 1.992.578 2.707 1.293l3 3C21.422 7.008 22 7.961 22 9v6c0 1.039-.578 1.992-1.293 2.707l-3 3C16.992 21.422 16.039 22 15 22H9c-1.039 0-1.992-.578-2.707-1.293l-3-3C2.578 16.992 2 16.039 2 15V9c0-1.039.578-1.992 1.293-2.707l3-3C7.008 2.578 7.961 2 9 2Z");
}

.ybi_gbb0b {
  d: path("M8 11a4 4 0 1 1 4 4a1 1 0 0 1 0-2a2 2 0 1 0-2-2a1 1 0 0 1-2 0m4 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
