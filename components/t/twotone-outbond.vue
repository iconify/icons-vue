<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmgwlmy6j"/><path class="cj8lthylx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-outbond" /></template>
<style>
.cj8lthylx {
  fill: currentColor;
  d: path("M12 4c4.41 0 8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8s3.59-8 8-8m0-2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m1.88 9.54L8.92 16.5l-1.41-1.41l4.96-4.96L10.34 8l5.65.01l.01 5.65z");
}

.nmgwlmy6j {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8m1.88 7.54L8.92 16.5l-1.41-1.41l4.96-4.96L10.34 8l5.65.01l.01 5.65z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
