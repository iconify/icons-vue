<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v92_nr68a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:washing-machine-off" /></template>
<style>
.v92_nr68a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.8715 19.8715C19.4981 21.1033 18.3538 22 17 22L7 22C5.3431 22 4 20.6569 4 19L4 5C4 4.6969 4.0449 4.4043 4.1285 4.1285M15.6465 15.6465C15.0188 17.0343 13.6222 18 12 18C9.7909 18 8 16.2091 8 14C8 12.3778 8.9657 10.9812 10.3535 10.3535M7.6569 2L17 2C18.6569 2 20 3.3431 20 5L20 14.3431M12 6L16 6M2 2L22 22");
}

</style>
