<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grjtoib3d"/><path class="s2r_q-ofk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bedtime" /></template>
<style>
.grjtoib3d {
  fill: currentColor;
  d: path("M9.27 4.49A8 8 0 0 0 4 12c0 4.41 3.59 8 8 8c1.81 0 3.54-.62 4.93-1.71c-3.91-1.39-9.29-6.26-7.66-13.8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s2r_q-ofk {
  fill: currentColor;
  d: path("M12.34 2.02c-.12 0-.23-.01-.35-.01C6.4 2.01 2 6.54 2 12c0 5.52 4.48 10 10 10c3.71 0 6.93-2.02 8.66-5.02c-7.51-.25-12.09-8.43-8.32-14.96M12 20c-4.41 0-8-3.59-8-8c0-3.45 2.2-6.4 5.27-7.51c-1.63 7.54 3.75 12.41 7.66 13.8A8 8 0 0 1 12 20");
}

</style>
