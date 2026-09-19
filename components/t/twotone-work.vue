<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqhhvvbte"/><path class="sh_g4j23e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-work" /></template>
<style>
.rqhhvvbte {
  fill: currentColor;
  d: path("M4 8h16v11H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.sh_g4j23e {
  fill: currentColor;
  d: path("M20 6h-4V4c0-1.11-.89-2-2-2h-4c-1.11 0-2 .89-2 2v2H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2M10 4h4v2h-4zm10 15H4V8h16z");
}

</style>
