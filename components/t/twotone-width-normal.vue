<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfn90sbke"/><path class="yxpl29b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-width-normal" /></template>
<style>
.sfn90sbke {
  fill: currentColor;
  d: path("M10 6h4v12h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yxpl29b3q {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M8 18H4V6h4zm6 0h-4V6h4zm6 0h-4V6h4z");
}

</style>
