<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ak4rx1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-microphone-24-filled" /></template>
<style>
.v2ak4rx1b {
  fill: currentColor;
  d: path("M22.25 16a.75.75 0 0 1 .75.75a4.75 4.75 0 0 1-4 4.69v.81a.75.75 0 0 1-1.5 0v-.81a4.75 4.75 0 0 1-4-4.69a.75.75 0 0 1 1.5 0a3.25 3.25 0 0 0 6.5 0a.75.75 0 0 1 .75-.75m-3-12A2.75 2.75 0 0 1 22 6.75v8.27a1.8 1.8 0 0 0-.5.15v-.92a3.25 3.25 0 0 0-6.5 0v.92a1.75 1.75 0 0 0-2.5 1.58A5.7 5.7 0 0 0 13.506 20H4.75A2.75 2.75 0 0 1 2 17.25V6.75A2.75 2.75 0 0 1 4.75 4zm-1 8a2.25 2.25 0 0 1 2.25 2.25v2.5a2.25 2.25 0 0 1-4.5 0v-2.5A2.25 2.25 0 0 1 18.25 12m-11.5 2a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zm0-3a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zm0-3a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
