<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okp58vejz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:reagent-bottle" /></template>
<style>
.okp58vejz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.875 1.75h-3.75q-2.375 0-2.375 2.375q0 1.541 1 2.082V7.75H7q-2.75 0-2.75 2.75v9q0 2.75 2.75 2.75h10q2.75 0 2.75-2.75v-9q0-2.75-2.75-2.75h-1.75V6.207q1-.541 1-2.082q0-2.375-2.375-2.375M13.75 6.5v2q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014H17q1.25 0 1.25 1.25v9q0 1.25-1.25 1.25H7q-1.25 0-1.25-1.25v-9q0-1.25 1.25-1.25h2.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2zm-.102 5.674l1.203 1.295q1.423 1.531 0 3.063l-1.203 1.294q-.667.719-1.648.719t-1.648-.719l-1.203-1.295q-1.423-1.531 0-3.062l1.203-1.295q.667-.719 1.648-.719t1.648.719");
}

</style>
