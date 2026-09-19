<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfzn95nys"/><path class="gsbh35b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-move-to-inbox" /></template>
<style>
.gsbh35b3k {
  fill: currentColor;
  d: path("M16 9h-2.55V6h-2.9v3H8l4 4zm3-6H4.99C3.88 3 3 3.9 3 5v14c0 1.1.88 2 1.99 2H19c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5v-3h3.56c.69 1.19 1.97 2 3.45 2s2.75-.81 3.45-2H19zm0-5h-4.99c0 1.1-.9 2-2 2s-2-.9-2-2H5l-.01-9H19z");
}

.hfzn95nys {
  fill: currentColor;
  d: path("M12.01 18c-1.48 0-2.75-.81-3.45-2H5v3h14v-3h-3.55a3.98 3.98 0 0 1-3.44 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
