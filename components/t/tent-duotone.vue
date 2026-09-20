<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mdm4t5b9e"/><path class="cv7j4gi0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tent-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cv7j4gi0w {
  d: path("m255.31 188.75l-64-144A8 8 0 0 0 184 40H72a8 8 0 0 0-7.27 4.69a.2.2 0 0 0 0 .06v.12L.69 188.75A8 8 0 0 0 8 200h240a8 8 0 0 0 7.31-11.25M64 184H20.31L64 85.7Zm16 0V85.7l43.69 98.3Zm61.2 0L84.31 56h94.49l56.89 128Z");
}

.mdm4t5b9e {
  d: path("M136 192H8L72 48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
