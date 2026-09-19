<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omuvm3g-k"/><path class="y91ngkbyd"/><circle class="t6wz8cb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-church" /></template>
<style>
.omuvm3g-k {
  fill: currentColor;
  d: path("M16 10.04L12 8l-4 2.04v3.35L4 15.2V20h5v-2.04c0-1.69 1.35-3.06 3-3.06s3 1.37 3 3.06V20h5v-4.79l-4-1.81zm-4 3.46c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t6wz8cb3t {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

.y91ngkbyd {
  fill: currentColor;
  d: path("M18 12.22V9l-5-2.5V5h2V3h-2V1h-2v2H9v2h2v1.5L6 9v3.22L2 14v8h9v-4c0-.55.45-1 1-1s1 .45 1 1v4h9v-8zM20 20h-5v-2.04c0-1.69-1.35-3.06-3-3.06s-3 1.37-3 3.06V20H4v-4.79l4-1.81v-3.35L12 8l4 2.04v3.35l4 1.81z");
}

</style>
