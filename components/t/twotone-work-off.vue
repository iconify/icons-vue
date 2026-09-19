<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8-07ufbm"/><path class="c-kp_gubj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-work-off" /></template>
<style>
.c-kp_gubj {
  fill: currentColor;
  d: path("M10 4h4v2h-3.6l2 2H20v7.6l2 2V8c0-1.11-.89-2-2-2h-4V4c0-1.11-.89-2-2-2h-4c-.99 0-1.8.7-1.96 1.64L10 5.6zM3.4 1.84L1.99 3.25L4.74 6H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h15.74l2 2l1.41-1.41zM4 19V8h2.74l11 11z");
}

.k8-07ufbm {
  fill: currentColor;
  d: path("M4 8v11h13.74l-11-11zm8.4 0l7.6 7.6V8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
