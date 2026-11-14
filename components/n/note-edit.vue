<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmo__wbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:note-edit" /></template>
<style>
.tmo__wbbh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-2.75 2.75-2.75h12q2.75 0 2.75 2.75v8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 13.25h-4q-2.75 0-2.75 2.75v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6q-2.75 0-2.75-2.75zm11.108 1.142q-1.237-1.237-2.474 0L8.316 10.71q-.482.481-.615 1.149l-.088.439q-.142.709.369 1.22t1.22.369l.439-.088q.668-.133 1.149-.615l3.568-3.568q1.237-1.237 0-2.474M20 14.75q.149 0 .287-.057t.243-.163l-6 6q.106-.105.163-.243T14.75 20v-4q0-1.25 1.25-1.25z");
}

</style>
