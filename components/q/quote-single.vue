<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5g4_cb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:quote-single" /></template>
<style>
.z5g4_cb3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 3.25h6q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7q0 7.707-7.513 10.212q-.07.023-.143.032t-.147.004t-.145-.025q-.071-.019-.137-.052t-.125-.079t-.107-.101t-.085-.12q-.036-.064-.06-.134l-.5-1.5q-.021-.064-.03-.13q-.01-.066-.008-.134q.003-.067.017-.132q.014-.066.04-.128t.062-.119t.082-.105t.1-.09q.054-.04.114-.07q2.837-1.418 3.454-4.079H10q-2.75 0-2.75-2.75V6q0-2.75 2.75-2.75");
}

</style>
