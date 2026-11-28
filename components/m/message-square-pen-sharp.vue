<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liaou-bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-pen-sharp" /></template>
<style>
.liaou-bds {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3L3 3L3 21L7 17L21 17L21 11M11 13L15.1248 11.3501L20.4874 5.9874C21.1709 5.304 21.1709 4.196 20.4874 3.5126C19.804 2.8291 18.696 2.8291 18.0126 3.5126L12.6499 8.8752Z");
}

</style>
