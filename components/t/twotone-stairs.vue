<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wan4y3epy"/><path class="jri1f1aua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-stairs" /></template>
<style>
.jri1f1aua {
  fill: currentColor;
  d: path("M19 5v14H5V5zm0-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-1 3h-4.42v3.33H11v3.33H8.42V16H6v2h4.42v-3.33H13v-3.33h2.58V8H18z");
}

.wan4y3epy {
  fill: currentColor;
  d: path("M19 5v14H5V5zm-1 1h-4.42v3.33H11v3.33H8.42V16H6v2h4.42v-3.33H13v-3.33h2.58V8H18z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
