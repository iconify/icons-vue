<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al5jx2bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:utensils" /></template>
<style>
.al5jx2bby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 2C17.6568 2 19 3.7909 19 6C19 8.2091 17.6568 10 16 10C14.3431 10 13 8.2091 13 6C13 3.7909 14.3431 2 16 2ZM5 13L8.5 13C8.7761 13 9 12.7761 9 12.5L9 8.862C9 6.1485 7.6021 3.6263 5.301 2.1881C5.17 2.1062 5 2.2005 5 2.355ZM16 10L16 22M5 13L5 22");
}

</style>
