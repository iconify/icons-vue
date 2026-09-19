<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo_f-ybkx"/><path class="dcdep_b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-diamond" /></template>
<style>
.dcdep_b6e {
  fill: currentColor;
  d: path("M19 3H5L2 9l10 12L22 9zm-1.24 2l1.5 3h-2.65l-1.5-3zM6.24 5h2.65l-1.5 3H4.74zM11 16.68L5.44 10H11zM9.62 8l1.5-3h1.76l1.5 3zM13 16.68V10h5.56z");
}

.uo_f-ybkx {
  fill: currentColor;
  d: path("M8.88 5H6.24l-1.5 3h2.64zm10.38 3l-1.5-3h-2.64l1.5 3zM11 16.68V10H5.44zm2 0L18.56 10H13zM12.88 5h-1.76l-1.5 3h4.76z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
