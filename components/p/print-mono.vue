<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgpi98b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:print-mono" /></template>
<style>
.jgpi98b_i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 5.75V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 1.75 7 1.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.25h1.75q2.75 0 2.75 2.75V14q0 2.75-2.75 2.75h-.75v3q0 1.036-.732 1.768t-1.768.732h-8.5q-1.036 0-1.768-.732T5.25 19.75v-3H4.5q-2.75 0-2.75-2.75V8.5q0-1.139.805-1.945q.806-.805 1.945-.805zm1.5 0h8.5v-2.5h-8.5zm11.75 9.5h-.75v-2q0-1.036-.732-1.768t-1.768-.732h-8.5q-2.5 0-2.5 2.5v2H4.5q-1.25 0-1.25-1.25V8.5q0-.518.366-.884T4.5 7.25h15q1.25 0 1.25 1.25V14q0 1.25-1.25 1.25M15 16.5q0-3-2.999-3H12q-3 0-3 3t3 3h.001q2.999 0 2.999-3");
}

</style>
