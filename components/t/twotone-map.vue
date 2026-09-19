<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6vc6ibvc"/><path class="p8qglccec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-map" /></template>
<style>
.o6vc6ibvc {
  fill: currentColor;
  d: path("m5 18.31l3-1.16V5.45L5 6.46zm11 .24l3-1.01V5.69l-3 1.17z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.p8qglccec {
  fill: currentColor;
  d: path("m20.5 3l-.16.03L15 5.1L9 3L3.36 4.9c-.21.07-.36.25-.36.48V20.5c0 .28.22.5.5.5l.16-.03L9 18.9l6 2.1l5.64-1.9c.21-.07.36-.25.36-.48V3.5c0-.28-.22-.5-.5-.5M8 17.15l-3 1.16V6.46l3-1.01zm6 1.38l-4-1.4V5.47l4 1.4zm5-.99l-3 1.01V6.86l3-1.16z");
}

</style>
