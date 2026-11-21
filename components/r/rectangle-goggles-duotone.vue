<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxgjljysu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rectangle-goggles-duotone" /></template>
<style>
.oxgjljysu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 8V16C22 17.1046 21.1046 18 20 18H16.9612C16.3537 18 15.7791 17.7238 15.3995 17.2494L12.7809 13.9761C12.3805 13.4757 11.6195 13.4757 11.2191 13.9761L8.60049 17.2494C8.22094 17.7238 7.64632 18 7.03875 18H4C2.89543 18 2 17.1046 2 16V8C2 6.89543 2.89543 6 4 6H20C21.1046 6 22 6.89543 22 8Z");
}

</style>
