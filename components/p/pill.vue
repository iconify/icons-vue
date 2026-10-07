<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_y6n2e0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pill" /></template>
<style>
.h_y6n2e0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.9948 4.3735C13.8742 3.4941 15.0669 3 16.3106 3C17.5543 3 18.7471 3.4941 19.6265 4.3735C20.5059 5.2529 21 6.4457 21 7.6894C21 8.9331 20.5059 10.1258 19.6265 11.0052L11.0052 19.6265C10.1258 20.5059 8.9331 21 7.6894 21C6.4457 21 5.2529 20.5059 4.3735 19.6265C3.4941 18.7471 3 17.5543 3 16.3106C3 15.0669 3.4941 13.8742 4.3735 12.9948L12.9948 4.3735ZM8.6841 8.6841L15.3159 15.3159");
}

</style>
