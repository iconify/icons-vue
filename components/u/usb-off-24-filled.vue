<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dalw7zbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-off-24-filled" /></template>
<style>
.dalw7zbsn {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-6.74-6.74l-.494.454A1.5 1.5 0 0 0 13 16.6v1.67A1.998 1.998 0 0 1 12 22a1.998 1.998 0 0 1-1.032-3.71a1.5 1.5 0 0 0-.454-.796l-4.38-4.014A3.5 3.5 0 0 1 5 10.9v-.17a1.998 1.998 0 0 1 .941-3.728L2.22 3.28a.75.75 0 0 1 0-1.06m5.777 6.838A2 2 0 0 1 7 10.73v.17c0 .42.177.822.486 1.106L11 15.226V12.06zM19.25 5a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75h-.253a3.5 3.5 0 0 1-1.132 2.48l-1.672 1.532l-1.416-1.416l1.737-1.59c.285-.261.455-.623.481-1.006h-.245a.75.75 0 0 1-.75-.75v-2.5a.75.75 0 0 1 .75-.75zm-7.893-3.635a.75.75 0 0 1 1.287 0l1.499 2.497a.75.75 0 0 1-.643 1.136H13v4.82l-2-2v-2.82h-.498a.75.75 0 0 1-.644-1.136z");
}

</style>
