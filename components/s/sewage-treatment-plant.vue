<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wumctn9lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sewage-treatment-plant" /></template>
<style>
.wumctn9lb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6q0-2.75 4.5-2.75T10.75 6v9.75h1.5V11.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.727q1.882-.707 3.916.649q1.638 1.092 3.084.226V11.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7q0 2.75-2.75 2.75H15q-2.75 0-2.75-2.75v-1.25h-1.5v1.25q0 2.75-4.5 2.75t-4.5-2.75zm12 10.5v2q0 1.25 1.25 1.25h4.5q1.25 0 1.25-1.25v-2.727q-1.882.707-3.916-.649q-1.638-1.092-3.084-.226zm-4.5 0V8.259q-1.098.491-3 .491t-3-.491V18.5q0 1.25 3 1.25t3-1.25z");
}

</style>
