<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2ltg6v_y"/><path class="cexb17ojl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mode-edit-outline" /></template>
<style>
.cexb17ojl {
  fill: currentColor;
  d: path("M3 17.25V21h3.75L17.81 9.94l-3.75-3.75zM5.92 19H5v-.92l9.06-9.06l.92.92zM20.71 5.63l-2.34-2.34a.996.996 0 0 0-1.41 0l-1.83 1.83l3.75 3.75l1.83-1.83a.996.996 0 0 0 0-1.41");
}

.j2ltg6v_y {
  fill: currentColor;
  d: path("M5 18.08V19h.92l9.06-9.06l-.92-.92z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
