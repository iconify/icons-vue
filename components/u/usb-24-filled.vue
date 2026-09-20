<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8s1tmhiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-24-filled" /></template>
<style>
.k8s1tmhiv {
  fill: currentColor;
  d: path("M11.357 1.365a.75.75 0 0 1 1.287 0l1.499 2.497a.75.75 0 0 1-.643 1.136H13v8.228l3.514-3.22c.285-.262.456-.622.481-1.006h-.245a.75.75 0 0 1-.75-.75v-2.5a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75h-.253a3.5 3.5 0 0 1-1.132 2.48l-4.379 4.014A1.5 1.5 0 0 0 13 16.6v1.67A1.998 1.998 0 0 1 12 22a2 2 0 0 1-1.032-3.71a1.5 1.5 0 0 0-.454-.796l-4.38-4.014A3.5 3.5 0 0 1 5 10.9v-.17A1.997 1.997 0 0 1 6 7a2 2 0 0 1 1 3.73v.17c0 .42.177.822.486 1.106L11 15.226V4.998h-.498a.75.75 0 0 1-.644-1.136z");
}

</style>
