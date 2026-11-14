<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2lja0r0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spade-suit" /></template>
<style>
.a2lja0r0z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.478 1.962l-.016.016l-8 8.25l-.016.017q-1.761 1.931-1.376 4.516t2.632 3.919q2.191 1.301 4.578.478q-.147.823.358 1.585q.667 1.006 1.875 1.007h.974q1.208-.001 1.875-1.007q.505-.762.358-1.585q2.387.823 4.578-.478q2.247-1.334 2.632-3.919t-1.376-4.516l-.016-.017l-8-8.25q-.103-.107-.24-.166t-.286-.062q-.15-.002-.288.053q-.139.055-.246.159");
}

</style>
