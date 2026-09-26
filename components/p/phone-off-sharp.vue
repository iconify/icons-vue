<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgxtdubrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-off-sharp" /></template>
<style>
.jgxtdubrx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.3288 14.4286C3.1634 11.3823 2 7.7375 2 4L2 2L9 2L9 8L7.0953 9.4285C7.4054 10.1656 7.778 10.8748 8.2091 11.5482M10.1005 13.8995C11.3822 15.1812 12.9007 16.2018 14.5715 16.9047L16 15L22 15L22 22L20 22C15.2261 22 10.6477 20.1036 7.2721 16.7279M22.2929 1.7071L1.7071 22.2929");
}

</style>
