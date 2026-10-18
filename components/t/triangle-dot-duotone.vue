<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yygold0ba"/><path class="q7lztj58y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-dot-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q7lztj58y {
  d: path("M14 14C14 15.1046 13.1046 16 12 16C10.8954 16 10 15.1046 10 14C10 12.8954 10.8954 12 12 12C13.1046 12 14 12.8954 14 14Z");
}

.yygold0ba {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.7328 3.8869C10.2061 1.3716 13.7947 1.3715 15.268 3.8869L22.4623 16.172C23.9502 18.7134 22.1759 21.9998 19.1947 22.0002L4.8061 22.0002C1.8245 22.0001 0.0502 18.7136 1.5385 16.172L8.7328 3.8869Z");
}

</style>
