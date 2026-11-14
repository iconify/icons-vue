<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgzvsvb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:working-hours-law" /></template>
<style>
.mgzvsvb8n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.975 6.586L18.389 8q.733.732.733 1.767q0 1.036-.733 1.768l-.354.354q-.732.733-1.768.733q-1.035 0-1.767-.733L10.611 8q-.733-.732-.733-1.767q0-1.036.733-1.768l.354-.354q.732-.733 1.767-.733q1.036 0 1.768.733l1.415 1.414L19.72 1.72q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T21 2.25t-.057.287t-.163.243zM2.861 11.611Q1.25 13.222 1.25 15.5t1.611 3.889T6.75 21t3.889-1.611T12.25 15.5t-1.611-3.889T6.75 10t-3.889 1.611M15.75 16.75H20q2.25 0 2.25 2.25T20 21.25h-4.25q-2.25 0-2.25-2.25t2.25-2.25");
}

</style>
