<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5wg2nbix"/><path class="b9dakknle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-looks-4" /></template>
<style>
.a5wg2nbix {
  fill: currentColor;
  d: path("M5.04 19h14V5h-14zm4-12h2v4h2V7h2v10h-2v-4h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.b9dakknle {
  fill: currentColor;
  d: path("M19.04 3h-14c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16h-14V5h14zm-6-2h2V7h-2v4h-2V7h-2v6h4z");
}

</style>
