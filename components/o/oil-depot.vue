<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbrdekb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:oil-depot" /></template>
<style>
.qbrdekb9x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22.75 20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H2q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.116.035-.227t.103-.206q.067-.095.16-.165q.092-.07.202-.109V13q0-3.25 3.25-3.25T8.25 13v2.25h.5V8q0-3.25 3.25-3.25T15.25 8v7.25h.5V11q0-3.25 3.25-3.25T22.25 11v8.793q.11.039.202.109t.16.165t.103.206t.035.227m-7-3.75h-.5v3h.5zm-2-.75V8q0-1.75-1.75-1.75T10.25 8v11.75h3.5zm-5 .75h-.5v3h.5zm-2-.75v-3q0-1.75-1.75-1.75T3.25 13v6.75h3.5zm14 3.75V11q0-1.75-1.75-1.75T17.25 11v8.75z");
}

</style>
