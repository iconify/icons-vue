<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r93j_3rfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-network-wifi" /></template>
<style>
.r93j_3rfh {
  fill: currentColor;
  d: path("M12 4C7.31 4 3.07 5.9 0 8.98L12 21L24 8.98A16.88 16.88 0 0 0 12 4m0 4c-2.86 0-5.5.94-7.65 2.51L2.92 9.07C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07l-1.43 1.43A13 13 0 0 0 12 8");
}

</style>
