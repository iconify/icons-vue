<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv06nzb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-shield" /></template>
<style>
.qv06nzb0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2.25H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.25 2.926 3.25 3v8q0 7.432 8.445 11.185q.146.065.305.065t.305-.065Q20.75 18.432 20.75 11V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 2.25M8.032 13.145q-.243-1.278-.478-1.866q-1.252-3.13.746-4.629l.034-.024Q10.1 5.448 12 6.989q1.9-1.541 3.666-.363l.034.024q1.998 1.499.746 4.629q-.235.588-.478 1.866q-.249 1.309-.498 2.066q-.333 1.289-1.345 1.289q-1.023 0-1.353-1.318l-.488-1.952q-.033-.042-.284-.042t-.284.042l-.488 1.952q-.33 1.318-1.353 1.318q-1.012 0-1.345-1.289q-.249-.757-.498-2.066");
}

</style>
