<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmntd3bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ping-pong-player" /></template>
<style>
.dmntd3bpg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.995 3.495Q13.75 4.74 13.75 6.5q0 1.485.885 2.603l-2.307 5.243q-1.04-.596-2.328-.596H7q-1.968 0-3.359 1.391T2.25 18.5v3q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-1.346.952-2.298T7 15.25h3q3.25 0 3.25 3.25v3q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-1.838-1.214-3.173l2.275-5.173q.971.596 2.189.596q1.76 0 3.005-1.245T22.25 6.5t-1.245-3.005T18 2.25t-3.005 1.245M8.5 3.75q-3.75 0-3.75 3.75t3.75 3.75t3.75-3.75q0-1.553-1.098-2.652Q10.053 3.75 8.5 3.75");
}

</style>
