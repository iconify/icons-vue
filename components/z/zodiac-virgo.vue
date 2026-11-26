<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmtnnpbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-virgo" /></template>
<style>
.dmtnnpbte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 13L2 6C2 4.3431 3.3431 3 5 3C6.6569 3 8 4.3431 8 6L8 13M8 6C8 4.3431 9.3431 3 11 3C12.6569 3 14 4.3431 14 6L14 21M14 11L18 11C20.2091 11 22 12.7909 22 15C22 17.2091 20.2091 19 18 19L10 19");
}

</style>
