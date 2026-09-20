<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qydgcwbio"/><path class="dgy7mntzg"/><path class="wlsk3fbve"/><path class="u_-armb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shopping-bags" /></template>
<style>
.dgy7mntzg {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("m1 8l2 2l2-2l2 2l2-2l2 2l2-2l2 2l2-2l2 2l2-2v23H1z");
}

.qydgcwbio {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M11 0a8 8 0 0 0-8 8v8h2V8a6 6 0 0 1 12 0v8h2V8a8 8 0 0 0-8-8");
}

.u_-armb9h {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("m15 13l2 2l2-2l2 2l2-2l2 2l2-2l2 2l2-2l2 2l2-2v23H15z");
}

.wlsk3fbve {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M25 5a8 8 0 0 0-8 8v8h2v-8a6 6 0 0 1 12 0v8h2v-8a8 8 0 0 0-8-8");
}

</style>
