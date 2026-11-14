<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3orphb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:solid-state" /></template>
<style>
.n3orphb2t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5q0-3.25 3.25-3.25T8.25 5T5 8.25T1.75 5M12 1.75Q8.75 1.75 8.75 5T12 8.25T15.25 5T12 1.75M15.75 5q0-3.25 3.25-3.25T22.25 5T19 8.25T15.75 5M5 8.75q-3.25 0-3.25 3.25T5 15.25T8.25 12T5 8.75M8.75 12q0-3.25 3.25-3.25T15.25 12T12 15.25T8.75 12M19 8.75q-3.25 0-3.25 3.25T19 15.25T22.25 12T19 8.75M1.75 19q0-3.25 3.25-3.25T8.25 19T5 22.25T1.75 19M12 15.75q-3.25 0-3.25 3.25T12 22.25T15.25 19T12 15.75M15.75 19q0-3.25 3.25-3.25T22.25 19T19 22.25T15.75 19");
}

</style>
