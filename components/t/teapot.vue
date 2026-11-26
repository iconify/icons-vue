<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwx-debyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:teapot" /></template>
<style>
.qwx-debyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 16.5C20 16.5 18.5 11.5 22 11M6.2764 12.5H4C2.8954 12.5 2 13.3954 2 14.5C2 15.6046 2.8954 16.5 4 16.5H6M6 14C6 11.2386 8.6863 9 12 9C15.3137 9 18 11.2386 18 14V18C18 19.1046 17.1046 20 16 20H8C6.8954 20 6 19.1046 6 18V14ZM9 9.5V7C9 5.89543 9.89543 5 11 5H12M15 9.5V7C15 5.89543 14.1046 5 13 5H12M12 5V4");
}

</style>
