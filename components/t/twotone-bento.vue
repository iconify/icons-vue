<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0inqmepx"/><path class="jntnhsbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bento" /></template>
<style>
.j0inqmepx {
  fill: currentColor;
  d: path("M4 17h8V7H4zm4-6.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m6 2.5h6v4h-6zm6-6v4h-6V7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jntnhsbjn {
  fill: currentColor;
  d: path("M20 5H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m0 6h-6V7h6zM4 7h8v10H4zm10 10v-4h6v4zm-4.5-5c0 .83-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5");
}

</style>
