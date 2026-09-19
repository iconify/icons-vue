<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr-f_jb3w"/><path class="fw4oambdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-cottage" /></template>
<style>
.fw4oambdc {
  fill: currentColor;
  d: path("M12 3L6 7.58V6H4v3.11L1 11.4l1.21 1.59L4 11.62V21h16v-9.38l1.79 1.36L23 11.4zm6 16h-5v-4h-2v4H6v-8.9l6-4.58l6 4.58zM10 1c0 1.66-1.34 3-3 3c-.55 0-1 .45-1 1H4c0-1.66 1.34-3 3-3c.55 0 1-.45 1-1z");
}

.nr-f_jb3w {
  fill: currentColor;
  d: path("M18 19h-5v-4h-2v4H6v-8.9l6-4.58l6 4.58z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
