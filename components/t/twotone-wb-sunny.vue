<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa9m6kb6c"/><path class="wl4fmsexd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-wb-sunny" /></template>
<style>
.aa9m6kb6c {
  fill: currentColor;
  d: path("M12 7.5c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wl4fmsexd {
  fill: currentColor;
  d: path("m5.34 6.25l1.42-1.41l-1.8-1.79l-1.41 1.41zM1 10.5h3v2H1zM11 .55h2V3.5h-2zm7.66 5.705l-1.41-1.407l1.79-1.79l1.406 1.41zM17.24 18.16l1.79 1.8l1.41-1.41l-1.8-1.79zM20 10.5h3v2h-3zm-8-5c-3.31 0-6 2.69-6 6s2.69 6 6 6s6-2.69 6-6s-2.69-6-6-6m0 10c-2.21 0-4-1.79-4-4s1.79-4 4-4s4 1.79 4 4s-1.79 4-4 4m-1 4h2v2.95h-2zm-7.45-.96l1.41 1.41l1.79-1.8l-1.41-1.41z");
}

</style>
