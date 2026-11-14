<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0fbef8nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:neural-network" /></template>
<style>
.e0fbef8nl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1.25q-3.25 0-3.25 3.25q0 2.85 2.5 3.201v8.598q-2.5.351-2.5 3.201q0 3.25 3.25 3.25t3.25-3.25q0-.481-.071-.891l8.235-4.335q.805.976 2.586.976q3.25 0 3.25-3.25T19 8.75q-1.781 0-2.586.976L8.179 5.391q.071-.41.071-.891q0-3.25-3.25-3.25m10.821 11.641l-8.235 4.335q-.625-.757-1.836-.927V7.701q1.211-.17 1.836-.927l8.235 4.335q-.071.41-.071.891t.071.891");
}

</style>
