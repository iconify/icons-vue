<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="pyrtak96t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soccer-ball-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pyrtak96t {
  d: path("m12 8.166l-3.798 2.279L9.721 15h4.558l1.519-4.555Zm5.791 2.625l-1.688 5.061l1.729 2.593a1 1 0 0 1-1.664 1.11L14.465 17h-4.93l-1.703 2.555a1 1 0 0 1-1.664-1.11l1.729-2.593l-1.688-5.061l-2.525-.842a1.001 1.001 0 0 1 .632-1.898l2.564.855L11 6.434V3a1 1 0 0 1 2 0v3.434l4.12 2.472l2.564-.855a1.001 1.001 0 0 1 .632 1.898Z");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
