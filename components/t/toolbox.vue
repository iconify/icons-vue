<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8kldzb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toolbox" /></template>
<style>
.j8kldzb7h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 7.25h1.25q1.76 0 3.005 1.245T21.75 11.5V13q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 12.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094t-.093.113t-.07.13t-.043.14q-.014.073-.014.147v-1.5q0-1.76 1.245-3.005T6.5 7.25h1.25V5.5q0-2.25 2.25-2.25h4q.932 0 1.591.659T16.25 5.5zM2.25 13q0 .074.014.147q.015.072.043.14q.029.069.07.13t.093.113t.113.094t.13.069t.141.043q.072.014.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v3.5q0 1.76-1.245 3.005T17.5 20.75h-11q-1.76 0-3.005-1.245T2.25 16.5zm7-5.75V5.5q0-.75.75-.75h4q.75 0 .75.75v1.75z");
}

</style>
