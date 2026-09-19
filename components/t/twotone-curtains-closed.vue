<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmzj5_e3a"/><path class="g8_0hfy_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-curtains-closed" /></template>
<style>
.g8_0hfy_c {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM9 19H6V5h3zm4 0h-2V5h2zm5 0h-3V5h3z");
}

.lmzj5_e3a {
  fill: currentColor;
  d: path("M6 5h3v14H6zm9 0h3v14h-3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
