<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2c24ubgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-open-sharp" /></template>
<style>
.l2c24ubgr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.2413L8.1314 16.2413L2 12.7413L5 9.7413L12 6.2413L15.5449 2L22 5.2413L19 9.7413L19 18.618L12 22L5 18.618L5 14.4538M5 9.7413L12 13.2413L19 9.7413M12 13.2413L12 22M12 6.2413L19 9.7413");
}

</style>
