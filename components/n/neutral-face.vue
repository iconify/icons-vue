<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kr2i49omi"/><circle class="mlxqprb5m"/><circle class="v-gjr70hz"/><path class="fz-3q2bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:neutral-face" /></template>
<style>
.fz-3q2bfd {
  fill: currentColor;
  d: path("M38.871 44H25.127c-1.504 0-1.504 4 0 4h13.744c1.504 0 1.504-4 0-4");
}

.kr2i49omi {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30c16.566 0 30-13.432 30-30S48.566 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.163 59.5 32 59.5");
}

.mlxqprb5m {
  cx: 20.5px;
  cy: 27.592px;
  r: 5px;
  fill: currentColor;
}

.v-gjr70hz {
  cx: 43.498px;
  cy: 27.592px;
  r: 5px;
  fill: currentColor;
}

</style>
