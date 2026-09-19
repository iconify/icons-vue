<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8fvd828h"/><path class="xivdv8u9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-brightness-1" /></template>
<style>
.xivdv8u9v {
  fill: currentColor;
  d: path("M12 22c5.52 0 10-4.48 10-10S17.52 2 12 2S2 6.48 2 12s4.48 10 10 10m0-18c4.41 0 8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8s3.59-8 8-8");
}

.y8fvd828h {
  fill: currentColor;
  d: path("M12 20c4.41 0 8-3.59 8-8s-3.59-8-8-8s-8 3.59-8 8s3.59 8 8 8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
