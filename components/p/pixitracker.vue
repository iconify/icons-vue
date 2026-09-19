<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjbqon33e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixitracker" /></template>
<style>
.mjbqon33e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.579 11.697v4.921h-4.921v-4.921zV6.776H10.422v4.921h4.921v4.921h-4.92v-4.921H5.5v9.842h4.921v4.922H5.5v14.763h4.921v-9.842H21.54v9.842h4.921v-9.842H37.58v9.842h4.92V26.461h-4.92v-4.922h4.92v-9.842zm-4.921 14.764H15.343v-4.922h17.315z");
}

</style>
