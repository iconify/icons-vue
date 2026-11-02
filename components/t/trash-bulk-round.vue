<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2kniu8dt"/><path class="e7pcij7ek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-bulk-round" /></template>
<style>
.a2kniu8dt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5h12a1 1 0 0 1 1 1v11a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5V6a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.e7pcij7ek {
  d: path("M16.874 5H20a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3.126A4 4 0 0 1 11 2h2a3.996 3.996 0 0 1 3.874 3M13 4h-2c-.715 0-1.376.38-1.733 1h5.466A1.99 1.99 0 0 0 13 4");
}

</style>
