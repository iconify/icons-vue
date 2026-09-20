<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap0thfbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-screen-time-24-regular" /></template>
<style>
.ap0thfbmf {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M13.75 2A2.25 2.25 0 0 1 16 4.25v6.924a6.5 6.5 0 0 0-1.5.558V4.25a.75.75 0 0 0-.75-.75h-7.5a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75l5.483.001a6.5 6.5 0 0 0 1.077 1.5L6.25 22A2.25 2.25 0 0 1 4 19.75V4.25A2.25 2.25 0 0 1 6.25 2zM8.749 17.504L11 17.499c0 .517.06 1.02.174 1.5l-2.423.005a.75.75 0 0 1-.002-1.5M16.5 14a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5h3.002a.5.5 0 0 0 0-1H17v-3.5a.5.5 0 0 0-.5-.5");
}

</style>
