<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls2vygber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooltip-top" /></template>
<style>
.ls2vygber {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 8.555q-.805.806-.805 1.945v8q0 2.75 2.75 2.75h15q2.75 0 2.75-2.75v-8q0-2.75-2.75-2.75h-4.584l-2.28-3.647q-.092-.147-.239-.239q-.062-.039-.131-.065t-.142-.039q-.073-.012-.147-.01q-.074.003-.146.019q-.072.017-.139.047t-.127.073t-.111.097t-.09.117L9.084 7.75H4.5q-1.139 0-1.945.805M15.5 13.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
