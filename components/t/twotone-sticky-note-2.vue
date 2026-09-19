<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm9na9bwr"/><path class="onmdt1zzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sticky-note-2" /></template>
<style>
.nm9na9bwr {
  fill: currentColor;
  d: path("M5 5v14h9v-5h5V5zm7 9H7v-2h5zm5-4H7V8h10z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.onmdt1zzh {
  fill: currentColor;
  d: path("M19 5v9h-5v5H5V5zm0-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h10l6-6V5c0-1.1-.9-2-2-2m-7 11H7v-2h5zm5-4H7V8h10z");
}

</style>
