<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n0l1q7b6f"/><path class="or-tzgb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-compass-calibration" /></template>
<style>
.n0l1q7b6f {
  cx: 12px;
  cy: 17px;
  r: 4px;
  fill: currentColor;
}

.or-tzgb2e {
  fill: currentColor;
  d: path("M12 3C8.1 3 4.56 4.59 2 7.15l5 5a7.06 7.06 0 0 1 10-.01l5-5C19.44 4.59 15.9 3 12 3");
}

</style>
