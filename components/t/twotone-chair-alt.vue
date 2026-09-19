<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myp4omjag"/><path class="i4ks_d9yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-chair-alt" /></template>
<style>
.i4ks_d9yh {
  fill: currentColor;
  d: path("M17 10c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v3c0 1.1.9 2 2 2h1v2H7c-1.1 0-2 .9-2 2v7h2v-3h10v3h2v-7c0-1.1-.9-2-2-2h-1v-2zm0 4v2H7v-2zm-7-2v-2h4v2zM7 8V5h10v3z");
}

.myp4omjag {
  fill: currentColor;
  d: path("M7 14h10v2H7zm0-9h10v3H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
