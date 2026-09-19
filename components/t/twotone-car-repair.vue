<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kstannb9w"/><circle class="up03czdem"/><circle class="ooy9bcqkc"/><path class="k67a_ebzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-car-repair" /></template>
<style>
.k67a_ebzj {
  fill: currentColor;
  d: path("M5.78 16h.44c.43 0 .78-.36.78-.81V14h10v1.19c0 .45.34.81.78.81h.44c.43 0 .78-.36.78-.81v-6.5L17.44 4c-.05-.16-.12-.29-.19-.4c-.02-.02-.03-.04-.05-.07c-.38-.52-.92-.53-.92-.53H7.72s-.54.01-.92.54c-.02.02-.03.04-.05.06c-.07.11-.14.24-.19.4L5 8.69v6.5c0 .45.35.81.78.81M8.33 5h7.34l.23.69l.43 1.31H7.67zM7 9.01V9h10v3H7zm-3 8V19h7v3h2v-3h7v-1.99z");
}

.kstannb9w {
  fill: currentColor;
  d: path("M17 9.01V9H7v3h10zM9 11.5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m6 0c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ooy9bcqkc {
  cx: 15px;
  cy: 10.5px;
  r: 1px;
  fill: currentColor;
}

.up03czdem {
  cx: 9px;
  cy: 10.5px;
  r: 1px;
  fill: currentColor;
}

</style>
