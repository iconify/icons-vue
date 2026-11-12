<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjkn6nbgz"/><path class="boa7bx3yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-square-bold-duotone" /></template>
<style>
.boa7bx3yi {
  fill: currentColor;
  d: path("M16.25 8a.75.75 0 0 1 1.5 0v8a.75.75 0 0 1-1.5 0zM7 12.75a.75.75 0 0 1 0-1.5h5.19l-1.72-1.72a.75.75 0 0 1 1.06-1.06l3 3a.75.75 0 0 1 0 1.06l-3 3a.75.75 0 1 1-1.06-1.06l1.72-1.72z");
}

.xjkn6nbgz {
  fill: currentColor;
  d: path("M2 12c0-4.714 0-7.071 1.464-8.536C4.93 2 7.286 2 12 2s7.071 0 8.535 1.464C22 4.93 22 7.286 22 12s0 7.071-1.465 8.535C19.072 22 16.714 22 12 22s-7.071 0-8.536-1.465C2 19.072 2 16.714 2 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
