<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwa0siozh"/><path class="jfg345bbh"/><path class="bn6ebpb5p"/><path class="zt59mfkop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dataset" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.jfg345bbh {
  fill: currentColor;
  d: path("M7 13h4v4H7zm6 0h4v4h-4z");
}

.pwa0siozh {
  fill: currentColor;
  d: path("M5 19h14V5H5zm8-12h4v4h-4zm0 6h4v4h-4zM7 7h4v4H7zm0 6h4v4H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zt59mfkop {
  fill: currentColor;
  d: path("M7 7h4v4H7zm6 0h4v4h-4z");
}

</style>
