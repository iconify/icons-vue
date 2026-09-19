<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi4sq1bek"/><path class="qz0333b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-calendar-today" /></template>
<style>
.qi4sq1bek {
  fill: currentColor;
  d: path("M20 3h-1V1h-2v2H7V1H5v2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 2v3H4V5zM4 21V10h16v11z");
}

.qz0333b8t {
  fill: currentColor;
  d: path("M4 5.01h16V8H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
