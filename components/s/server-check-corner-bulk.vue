<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sowt4_0jd"/><path class="mmius025n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-check-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mmius025n {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm6.697 10.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

.sowt4_0jd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8 8v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1");
}

</style>
