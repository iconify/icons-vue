<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm32sde0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-315-right-24-filled" /></template>
<style>
.wm32sde0a {
  fill: currentColor;
  d: path("M11.5 2a1 1 0 1 0 0 2h.086L8.543 7.043a1 1 0 0 0 1.414 1.414L13 5.414V5.5a1 1 0 1 0 2 0V3a1 1 0 0 0-1-1zM3.428 7.596a1 1 0 0 0-1.332 1.332l4.5 9.5a1 1 0 1 0 1.808-.856l-1.145-2.417l2.396-2.396l2.417 1.145a1 1 0 1 0 .856-1.808zm4.308 4.254L6.35 13.236l-1.248-2.634zM18.5 9a1 1 0 1 0 0 2h.086l-9.293 9.293a1 1 0 0 0 1.414 1.414L20 12.414v.086a1 1 0 1 0 2 0V10a1 1 0 0 0-1-1z");
}

</style>
