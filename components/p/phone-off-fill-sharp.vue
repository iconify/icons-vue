<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-tizsbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-fill-sharp" /></template>
<style>
.u-tizsbjq {
  fill: currentColor;
  d: path("m7.706 17.708l-4.999 4.999a.999.999 0 1 1-1.414-1.414l4.999-4.999A16.95 16.95 0 0 1 2 5V3a1 1 0 0 1 1-1h6c.409 0 .777.249.928.629l2 5a1 1 0 0 1-.221 1.078L9.414 11l1.086 1.086L21.293 1.293a.999.999 0 1 1 1.414 1.414Zm2.301.528l6.211-6.212a1 1 0 0 1 .153.048l5 2c.38.151.629.519.629.928v6a1 1 0 0 1-1 1h-2a17 17 0 0 1-9.714-3.043Z");
}

</style>
