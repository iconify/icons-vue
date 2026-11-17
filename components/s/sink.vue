<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2fwbcn5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sink" /></template>
<style>
.i2fwbcn5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 14H4M4 14V19C4 20.657 5.3431 22 7 22H17C18.6569 22 20 20.657 20 19V14M4 14H20M20 14H22M12 14V5C12 3.343 13.3431 2 15 2C16.6569 2 18 3.343 18 5V6M16 14V11C16 10.448 16.4477 10 17 10H20M8 14V11C8 10.448 7.5523 10 7 10H4");
}

</style>
