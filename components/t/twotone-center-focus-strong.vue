<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ihwennzfv"/><path class="w5qkwcbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-center-focus-strong" /></template>
<style>
.ihwennzfv {
  cx: 12px;
  cy: 12px;
  r: 3px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.w5qkwcbsp {
  fill: currentColor;
  d: path("M7 12c0 2.76 2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5s-5 2.24-5 5m8 0c0 1.65-1.35 3-3 3s-3-1.35-3-3s1.35-3 3-3s3 1.35 3 3M3 19c0 1.1.9 2 2 2h4v-2H5v-4H3zM3 5v4h2V5h4V3H5c-1.1 0-2 .9-2 2m18 0c0-1.1-.9-2-2-2h-4v2h4v4h2zm-2 14h-4v2h4c1.1 0 2-.9 2-2v-4h-2z");
}

</style>
