<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-gdnhb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vr-headset-alert" /></template>
<style>
.n-gdnhb-t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 2.75h-13q-1.346 0-2.298.952T2.25 6v2.5q0 3.25 3.25 3.25H9q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T9.75 11q0-2.25 2.25-2.25T14.25 11q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.5q1.346 0 2.298-.952T21.75 8.5V6q0-1.346-.952-2.298T18.5 2.75m1.499 13.239l1.538 2.979q.58 1.123-.077 2.203q-.658 1.079-1.922 1.079h-3.076q-1.264 0-1.922-1.079q-.657-1.08-.077-2.203l1.538-2.979q.628-1.218 1.999-1.218t1.999 1.218");
}

</style>
