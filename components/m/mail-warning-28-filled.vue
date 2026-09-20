<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="cdtbyrb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-warning-28-filled" /></template>
<style>
.cdtbyrb7y {
  fill: currentColor;
  d: path("M13.658 15.419c.215.11.47.11.684 0l.99-.507q.315.087.665.088h10.004v4.25a3.75 3.75 0 0 1-3.75 3.75H5.754a3.75 3.75 0 0 1-3.75-3.75v-9.8zm6.006-13.591c.553-1.104 2.12-1.104 2.672 0l5.002 9.992c.5 1-.222 2.18-1.336 2.18H15.998c-1.114 0-1.837-1.18-1.336-2.18zm-5.895 9.54a2.5 2.5 0 0 0 .138 2.492L2.004 7.764v-.013A3.75 3.75 0 0 1 5.754 4H17.46zM21 11a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-7a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5A.5.5 0 0 0 21 4");
}

</style>
