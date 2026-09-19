<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mbvdkwwxo"/><circle class="snmsf1bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tucan" /></template>
<style>
.mbvdkwwxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.478 25.415c-.958.115-1.92.257-2.831.571c-.912.314-1.78.812-2.408 1.544c-.668.778-1.032 1.782-1.181 2.797c-.15 1.014-.099 2.047-.02 3.07q.108 1.373.282 2.739a22.83 22.83 0 0 1-5.798-14.097c-.053-1.126-.02-2.262.201-3.368s.637-2.182 1.302-3.093c.862-1.18 2.114-2.038 3.467-2.592c1.353-.553 2.807-.818 4.261-.967c6.402-.66 12.867.86 18.836 3.268c2.032.82 4.037 1.75 5.814 3.033s3.327 2.941 4.226 4.94a10 10 0 0 1 .735 5.719a54.76 54.76 0 0 0-26.886-3.564");
}

.snmsf1bdz {
  cx: 11.195px;
  cy: 18.806px;
  r: 3.524px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
