<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ast4nibig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:split-2-fill" /></template>
<style>
.ast4nibig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21V15M12 15C12 12 8.828 8.828 6 6L3.6 3.6M12 15C12 12 15.172 8.828 18 6L20.4 3.6M7 3H3.5C3.224 3 3 3.224 3 3.5V7M17 3H20.5C20.776 3 21 3.224 21 3.5V7");
}

</style>
