<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk7sodbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-event-available" /></template>
<style>
.yk7sodbsf {
  fill: currentColor;
  d: path("M16.53 11.06L15.47 10l-4.88 4.88l-2.12-2.12l-1.06 1.06L10.59 17zM21 3h-3V1h-2v2H8V1H6v2H3v18h18zm-2 16H5V8h14z");
}

</style>
