<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7i_10bdq"/><path class="laeym5-if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-1" /></template>
<style>
.l7i_10bdq {
  fill: currentColor;
  d: path("M7 17h14V3H7zm5-12h4v10h-2V7h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.laeym5-if {
  fill: currentColor;
  d: path("M14 15h2V5h-4v2h2zm7-14H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14zM1 5v16c0 1.1.9 2 2 2h16v-2H3V5z");
}

</style>
