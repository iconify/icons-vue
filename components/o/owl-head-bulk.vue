<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fin-xjjjc"/><path class="m_ycx9e0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-head-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fin-xjjjc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.625 2.219c1.074.859 2.254 1.605 3.543 2.097c1.225.461 2.524.693 3.832.684a10.7 10.7 0 0 0 3.832-.684c1.289-.492 2.469-1.238 3.543-2.097a1 1 0 0 1 1.553.41c.522 1.304.809 2.693.942 4.089C22.006 8.14 22 9.572 22 11a11.8 11.8 0 0 1-.768 4.237c-.962 2.537-2.82 4.714-5.29 5.879A9.14 9.14 0 0 1 12 22c-4.254-.001-7.758-2.877-9.232-6.763A11.8 11.8 0 0 1 2 11c0-1.428-.006-2.86.13-4.282c.133-1.396.42-2.785.942-4.089a.998.998 0 0 1 1.553-.41");
}

.m_ycx9e0j {
  d: path("M8.707 10.293a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414M5 11.003V11a3 3 0 1 1 0 .003m11.707-.71a.999.999 0 1 0-1.414 1.414a.999.999 0 1 0 1.414-1.414M13 11a3 3 0 1 1 6 0a3 3 0 0 1-6 0m0 3a1 1 0 0 1 .894 1.447l-1 2a.998.998 0 0 1-1.788 0l-1-2A1 1 0 0 1 11 14Z");
}

</style>
