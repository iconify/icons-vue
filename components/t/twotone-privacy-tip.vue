<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sntvyfbuy"/><path class="dab2o5k1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-privacy-tip" /></template>
<style>
.dab2o5k1x {
  fill: currentColor;
  d: path("m12 3.19l7 3.11V11c0 4.52-2.98 8.69-7 9.93c-4.02-1.24-7-5.41-7-9.93V6.3zM12 1L3 5v6c0 5.55 3.84 10.74 9 12c5.16-1.26 9-6.45 9-12V5zm-1 6h2v2h-2zm0 4h2v6h-2z");
}

.sntvyfbuy {
  fill: currentColor;
  d: path("M12 3.19L5 6.3V11c0 4.52 2.98 8.69 7 9.93c4.02-1.23 7-5.41 7-9.93V6.3zM13 17h-2v-6h2zm0-8h-2V7h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
