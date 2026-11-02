<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w2o-fqb9r"/><path class="e4loxhbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scissors-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e4loxhbti {
  d: path("M10.586 12L7.414 8.828a1 1 0 0 1 1.414-1.414L12 10.586l8.293-8.293a.999.999 0 1 1 1.414 1.414L8.828 16.586a1 1 0 0 1-1.414-1.414Zm11.121 8.293a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414Z");
}

.w2o-fqb9r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.315 4.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556m-1.842 9.665a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
