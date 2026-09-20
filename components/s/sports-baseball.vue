<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2zhgbchs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-baseball" /></template>
<style>
.t2zhgbchs {
  fill: currentColor;
  d: path("M5.194 17.917q-1.069-1.234-1.631-2.754T3 12t.563-3.162t1.631-2.755q1.412 1.029 2.17 2.599T8.12 12t-.757 3.318t-2.17 2.6m3.551 2.473q-1.55-.61-2.785-1.76q1.494-1.233 2.325-2.951q.83-1.719.83-3.68t-.83-3.68T5.96 5.37q1.234-1.15 2.785-1.76T12 3t3.255.61q1.55.61 2.785 1.76q-1.494 1.232-2.324 2.95q-.831 1.719-.831 3.68t.83 3.68t2.326 2.95q-1.235 1.15-2.786 1.76T12 21t-3.255-.61m10.06-2.473q-1.41-1.029-2.168-2.599T15.879 12t.758-3.318t2.169-2.6q1.069 1.235 1.631 2.756T21 12t-.562 3.163t-1.632 2.754");
}

</style>
