<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfx4ftshp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:org-chart-government" /></template>
<style>
.jfx4ftshp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 2.25h2.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-.5v2H18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.75h.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-1.5q0-2.5 2.5-2.5h.5v-2H6.75v2h.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-1.5q0-2.5 2.5-2.5h.5V11.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 10.75h5.25v-2h-.5q-2.5 0-2.5-2.5v-1.5q0-2.5 2.5-2.5");
}

</style>
