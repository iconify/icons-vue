<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt_mqcbkw"/><path class="ercr9nyht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-charging-20" /></template>
<style>
.ercr9nyht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v13h4v-2.5H9L13 7v5.5h2L12.6 17H17z");
}

.xt_mqcbkw {
  fill: currentColor;
  d: path("M11 20v-3H7v5h10v-5h-4.4z");
}

</style>
