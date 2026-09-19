<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rls2mumyh"/><path class="bn6ebpb5p"/><path class="h-8ozmb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-analytics" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.h-8ozmb-q {
  fill: currentColor;
  d: path("M7 12h2v5H7zm8-5h2v10h-2zm-4 7h2v3h-2zm0-4h2v2h-2z");
}

.rls2mumyh {
  fill: currentColor;
  d: path("M5 5h14v14H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
