<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4efoq1vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mails" /></template>
<style>
.n4efoq1vt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 13L2 7C2 5.3431 3.3431 4 5 4L15 4M9 8L19 8C20.6569 8 22 9.3431 22 11L22 17C22 18.6569 20.6569 20 19 20L9 20C7.3431 20 6 18.6569 6 17L6 11C6 9.3431 7.3431 8 9 8ZM6 11L13.6046 14.2733C13.857 14.3819 14.143 14.3819 14.3954 14.2733L22 11");
}

</style>
