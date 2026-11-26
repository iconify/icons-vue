<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi6dtv1ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:superscript-sharp" /></template>
<style>
.zi6dtv1ge {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7681 7.7217L2 8L12 20L12.2998 20.3598M12.2998 7.6402L12 8L1.7704 20.3625M16.4323 6.3965L16.75 6.1L19 4L19 11M15 11L23 11");
}

</style>
