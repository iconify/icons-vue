<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2wtxpb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mountain-bulk-sharp" /></template>
<style>
.g2wtxpb1o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.106 10.553l3-6a.998.998 0 0 1 1.788 0L13 8.764l1.106-2.211a.998.998 0 0 1 1.788 0l6 12A1 1 0 0 1 21 20H3a1 1 0 0 1-.894-1.447Z");
}

</style>
