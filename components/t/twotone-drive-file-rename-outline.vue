<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m440u6hyr"/><path class="xdha8xbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-drive-file-rename-outline" /></template>
<style>
.m440u6hyr {
  fill: currentColor;
  d: path("M12.06 10.02L5 17.08V18h.92l7.06-7.06z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xdha8xbyf {
  fill: currentColor;
  d: path("m15 16l-4 4h10v-4zm-2.94-8.81L3 16.25V20h3.75l9.06-9.06zM5.92 18H5v-.92l7.06-7.06l.92.92zm12.79-9.96a.996.996 0 0 0 0-1.41l-2.34-2.34a1 1 0 0 0-1.41 0l-1.83 1.83l3.75 3.75z");
}

</style>
