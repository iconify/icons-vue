<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am7wwubvr"/><path class="kb2oldbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-tour" /></template>
<style>
.am7wwubvr {
  fill: currentColor;
  d: path("M7 12V6h11.05l-1.2 3l1.2 3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.kb2oldbvp {
  fill: currentColor;
  d: path("M21 4H7V2H5v20h2v-8h14l-2-5zM7 12V6h11.05l-1.2 3l1.2 3zm7-3c0 1.1-.9 2-2 2s-2-.9-2-2s.9-2 2-2s2 .9 2 2");
}

</style>
