<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np3sipbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pants" /></template>
<style>
.np3sipbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.6025 7.06L20.9594 19.18C21.1788 20.3 20.4857 21.4 19.435 21.59L17.3228 21.97C16.4141 22.14 15.5301 21.56 15.2388 20.61L12.8881 12.99C12.6036 12.06 11.3963 12.06 11.1118 12.99L8.7612 20.61C8.4698 21.56 7.5859 22.14 6.6771 21.97L4.565 21.59C3.5143 21.4 2.8212 20.3 3.0406 19.18L5.3975 7.06L5.5945 6.05L6.2264 2.8C6.3176 2.34 6.6998 2 7.1425 2H16.8575C17.3002 2 17.6823 2.34 17.7736 2.8L18.4054 6.05L18.6025 7.06ZM5.3975 7.06H18.6025");
}

</style>
