<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyd3b2bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:merge" /></template>
<style>
.lyd3b2bgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2V10.648M15 5L12 2L9 5M12 10.648C12 14.707 13.671 18.497 16.453 20.748L18 22M12 10.648C12 14.707 10.329 18.497 7.547 20.748L6 22");
}

</style>
