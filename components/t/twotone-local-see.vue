<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2j9lfbfx"/><path class="n6e2ef43v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-see" /></template>
<style>
.n6e2ef43v {
  fill: currentColor;
  d: path("M4 20h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2h-3.17L15 2H9L7.17 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2M4 6h4.05l.59-.65L9.88 4h4.24l1.24 1.35l.59.65H20v12H4zm8 1c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m0 8.2c-1.77 0-3.2-1.43-3.2-3.2s1.43-3.2 3.2-3.2s3.2 1.43 3.2 3.2s-1.43 3.2-3.2 3.2");
}

.o2j9lfbfx {
  fill: currentColor;
  d: path("M20 6h-4.05l-.59-.65L14.12 4H9.88L8.65 5.35l-.6.65H4v12h16zm-8 11c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
