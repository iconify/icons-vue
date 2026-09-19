<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prp8dgy0l"/><path class="wtt2o_bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-signal-cellular-connected-no-internet-2-bar" /></template>
<style>
.prp8dgy0l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M22 8V2L2 22h16V8z");
}

.wtt2o_bsv {
  fill: currentColor;
  d: path("M14 22V10L2 22zm6-12v8h2v-8zm0 12h2v-2h-2z");
}

</style>
