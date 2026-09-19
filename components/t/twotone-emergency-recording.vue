<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcnw6vbov"/><path class="ag4b6eboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-emergency-recording" /></template>
<style>
.ag4b6eboh {
  fill: currentColor;
  d: path("M18 10.48V6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-4.48l4 3.98v-11zM16 18H4V6h12zm-4-6l3 1.73l-1 1.73l-3-1.73V17H9v-3.27l-3 1.73l-1-1.73L8 12l-3-1.73l1-1.73l3 1.73V7h2v3.27l3-1.73l1 1.73z");
}

.jcnw6vbov {
  fill: currentColor;
  d: path("M4 6v12h12V6zm11 7.73l-1 1.73l-3-1.73V17H9v-3.27l-3 1.73l-1-1.73L8 12l-3-1.73l1-1.73l3 1.73V7h2v3.27l3-1.73l1 1.73L12 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
