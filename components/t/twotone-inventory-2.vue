<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsmh58lbr"/><path class="xjvjsyuyj"/><path class="ads37eh-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-inventory-2" /></template>
<style>
.ads37eh-c {
  fill: currentColor;
  d: path("M9 12h6v2H9z");
}

.qsmh58lbr {
  fill: currentColor;
  d: path("M4 7h16V3.98L4 4zm1 13h14V9H5zm4-8h6v2H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xjvjsyuyj {
  fill: currentColor;
  d: path("M20 2H4c-1 0-2 .9-2 2v3.01c0 .72.43 1.34 1 1.69V20c0 1.1 1.1 2 2 2h14c.9 0 2-.9 2-2V8.7c.57-.35 1-.97 1-1.69V4c0-1.1-1-2-2-2m-1 18H5V9h14zm1-13H4V4l16-.02z");
}

</style>
