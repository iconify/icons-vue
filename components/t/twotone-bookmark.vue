<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ketz17bqs"/><path class="szsxebcbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bookmark" /></template>
<style>
.ketz17bqs {
  fill: currentColor;
  d: path("m7 17.97l5-2.15l5 2.15V5H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.szsxebcbu {
  fill: currentColor;
  d: path("M17 3H7c-1.1 0-2 .9-2 2v16l7-3l7 3V5c0-1.1-.9-2-2-2m0 14.97l-5-2.14l-5 2.14V5h10z");
}

</style>
