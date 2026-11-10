<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y63c87bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scribble-sharp-duotone" /></template>
<style>
.y63c87bqy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.68 13.54L2 13.25C5.5 10.01 11.942 4.22 13.111 3.46C14.778 2.37 16.712 3.39 17 5.09C17.556 8.35 11.445 13.25 8.667 15.97C5.889 18.69 8.667 20.86 10.889 19.78C12.38 19.05 17.086 13.76 18.667 13.25C20.334 12.7 21.445 14.34 20.334 15.97C19.359 17.4 17 20.32 18.111 20.86C19.223 21.41 20.889 20.32 22 19.23L22.301 18.94");
}

</style>
