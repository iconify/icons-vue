<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uni8accno"/><path class="h0wlzjbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-markunread-mailbox" /></template>
<style>
.h0wlzjbdq {
  fill: currentColor;
  d: path("M20 6H10v2h10v12H4V8h2v4h2V4h6V0H6v6H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2");
}

.uni8accno {
  fill: currentColor;
  d: path("M10 12H6V8H4v12h16V8H10z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
