<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu2wp5a9w"/><circle class="cbp_2nbuo"/><path class="mr6qhkbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-photo-camera-front" /></template>
<style>
.cbp_2nbuo {
  cx: 12px;
  cy: 11px;
  r: 2px;
  fill: currentColor;
}

.hu2wp5a9w {
  fill: currentColor;
  d: path("M20 5h-3.17L15 3H9L7.17 5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m0 14H4V7h4.05l1.83-2h4.24l1.83 2H20z");
}

.mr6qhkbmn {
  fill: currentColor;
  d: path("M14.78 14.58a6.95 6.95 0 0 0-5.56 0A2.01 2.01 0 0 0 8 16.43V17h8v-.57c0-.81-.48-1.53-1.22-1.85");
}

</style>
