<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rls2mumyh"/><path class="xugrx5b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-square" /></template>
<style>
.rls2mumyh {
  fill: currentColor;
  d: path("M5 5h14v14H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xugrx5b8f {
  fill: currentColor;
  d: path("M3 3v18h18V3zm16 16H5V5h14z");
}

</style>
