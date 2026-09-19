<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4jinik_l"/><path class="adpdxdbba"/><circle class="xzditrbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-flashlight-on" /></template>
<style>
.adpdxdbba {
  fill: currentColor;
  d: path("M6 2v6l2 3v11h8V11l2-3V2zm10 5.39l-2 3.01V20h-4v-9.61l-2-3V7h8zM16 5H8V4h8z");
}

.o4jinik_l {
  fill: currentColor;
  d: path("m8 7.39l2 3V20h4v-9.6l2-3.01V7H8zm4 5.11c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5M8 4h8v1H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xzditrbqy {
  cx: 12px;
  cy: 14px;
  r: 1.5px;
  fill: currentColor;
}

</style>
