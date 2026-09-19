<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq8sdfdop"/><path class="gsz4t6bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mode-comment" /></template>
<style>
.gsz4t6bvt {
  fill: currentColor;
  d: path("M4 4v12h14.83L20 17.17V4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pq8sdfdop {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14l4 4V4c0-1.1-.9-2-2-2m0 15.17L18.83 16H4V4h16z");
}

</style>
