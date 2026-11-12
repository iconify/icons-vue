<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mpbsz3eep"/><path class="uoqp86beu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:regex-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mpbsz3eep {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.236 17.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.uoqp86beu {
  d: path("m17 6l2.4-1.8a1 1 0 0 1 1.2 1.6L17.667 8l2.933 2.2a1 1 0 0 1-1.2 1.6L17 10v3a1 1 0 0 1-2 0v-3l-2.4 1.8a1 1 0 0 1-1.2-1.6L14.333 8L11.4 5.8a1 1 0 0 1 1.2-1.6L15 6V3a1 1 0 0 1 2 0Z");
}

</style>
