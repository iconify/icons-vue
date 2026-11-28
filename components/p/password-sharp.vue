<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxoa7hbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:password-sharp" /></template>
<style>
.mxoa7hbvp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 6L4 13M1.6 11.3L6.4 7.7M1.6 7.7L6.4 11.3M12 6L12 13M9.6 11.3L14.4 7.7M9.6 7.7L14.4 11.3M20 6L20 13M17.6 11.3L22.4 7.7M17.6 7.7L22.4 11.3M1 17L23 17");
}

</style>
