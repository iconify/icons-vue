<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edhfktowk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vision-pro" /></template>
<style>
.edhfktowk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7L17 7C19.7614 7 22 9.2386 22 12C22 14.7614 19.7614 17 17 17C15.9945 17 15.0558 16.4962 14.5 15.6583C13.9442 14.8204 13.0055 14.3166 12 14.3166C10.9945 14.3166 10.0558 14.8204 9.5 15.6583C8.9442 16.4962 8.0055 17 7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7Z");
}

</style>
