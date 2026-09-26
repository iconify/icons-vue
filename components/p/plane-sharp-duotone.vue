<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-6ekh5os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane-sharp-duotone" /></template>
<style>
.x-6ekh5os {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.3777 6.8957L3.7367 5.2027L2.002 7.2022L8.4518 12.5M12.3777 6.8957M12.3777 6.8957L16.7849 3.6942C18.3007 2.5931 20.1262 2.0001 21.9998 2.0001C22 3.8248 21.3976 5.5984 20.2864 7.0458L16.9641 11.3727M12.3777 6.8957L6 16L2.631 16.6981L7.43 21.3248L8 18L16.9641 11.3727M11.5 15.5L17.1622 21.9981L19.2093 20.2862L16.9641 11.3727");
}

</style>
