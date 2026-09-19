<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1no3k8qw"/><path class="manzhlb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-assessment" /></template>
<style>
.manzhlb6g {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zM7 10h2v7H7zm4-3h2v10h-2zm4 6h2v4h-2z");
}

.t1no3k8qw {
  fill: currentColor;
  d: path("M5 5v14h14V5zm4 12H7v-7h2zm4 0h-2V7h2zm4 0h-2v-4h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
