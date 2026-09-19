<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cot-_itns"/><path class="z6lvnjcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-home" /></template>
<style>
.cot-_itns {
  fill: currentColor;
  d: path("M12 3L2 12h3v8h6v-6h2v6h6v-8h3zm5 15h-2v-6H9v6H7v-7.81l5-4.5l5 4.5z");
}

.z6lvnjcgg {
  fill: currentColor;
  d: path("M7 10.19V18h2v-6h6v6h2v-7.81l-5-4.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
