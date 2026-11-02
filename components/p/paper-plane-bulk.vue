<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xj7nahysi"/><path class="jwikj1bfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jwikj1bfu {
  d: path("m10.293 12.293l3-3a.999.999 0 1 1 1.414 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.xj7nahysi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.684 5.051l6-2a2.582 2.582 0 0 1 3.265 3.265l-4 12a3.2 3.2 0 0 1-.609 1.066c-.506.584-1.28 1.041-2.077.917a1.56 1.56 0 0 1-1.157-.852l-2.851-5.702l-5.702-2.851a1.56 1.56 0 0 1-.852-1.157c-.124-.797.333-1.571.917-2.077a3.2 3.2 0 0 1 1.066-.609Z");
}

</style>
