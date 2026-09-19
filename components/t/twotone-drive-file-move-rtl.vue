<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twfuznbnk"/><path class="jq-boqols"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-drive-file-move-rtl" /></template>
<style>
.jq-boqols {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 12H4V6h5.17l2 2H20zm-8-1l-4-4l4-4v3h4v2h-4z");
}

.twfuznbnk {
  fill: currentColor;
  d: path("m11.17 8l-2-2H4v12h16V8zM16 14h-4v3l-4-4l4-4v3h4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
