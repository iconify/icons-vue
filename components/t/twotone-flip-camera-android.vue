<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="lbgcdibwk"/><path class="heg9mvnjt"/><path class="gn9itpbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-flip-camera-android" /></template>
<style>
.gn9itpbye {
  fill: currentColor;
  d: path("M8 8H5.09C6.47 5.61 9.05 4 12 4c3.72 0 6.85 2.56 7.74 6h2.06c-.93-4.56-4.96-8-9.8-8c-3.27 0-6.18 1.58-8 4.01V4H2v6h6zm8 6v2h2.91c-1.38 2.39-3.96 4-6.91 4c-3.72 0-6.85-2.56-7.74-6H2.2c.93 4.56 4.96 8 9.8 8c3.27 0 6.18-1.58 8-4.01V20h2v-6z");
}

.heg9mvnjt {
  fill: currentColor;
  d: path("M9 12c0 1.66 1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3m4 0c0 .55-.45 1-1 1s-1-.45-1-1s.45-1 1-1s1 .45 1 1");
}

.lbgcdibwk {
  cx: 12px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
