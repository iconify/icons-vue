<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="thj7n1o7v"/><path class="k8y94cc3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tornado-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k8y94cc3e {
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-3 4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm1 4a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

.thj7n1o7v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Zm-5 6H9a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
