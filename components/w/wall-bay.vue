<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc0lk11nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wall-bay" /></template>
<style>
.gc0lk11nk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 1.75H5Q2.75 1.75 2.75 4v.5q0 1.592 1.127 2.058q-.127.407-.127.942v3.75h2.076q-.076-.337-.076-.75v-1q0-2.25 2.25-2.25h1q2.25 0 2.25 2.25v1q0 .413-.076.75h1.152q-.076-.337-.076-.75q0-2.25 2.25-2.25H16q2.25 0 2.25 2.25q0 .413-.076.75h2.076V7.5q0-.535-.127-.942Q21.25 6.092 21.25 4.5V4q0-2.25-2.25-2.25m1.25 11H3.75v4.75q0 .413.076.75h3q-.076-.337-.076-.75V16q0-2.25 2.25-2.25h.5q2.25 0 2.25 2.25v1.5q0 .413-.076.75h.652q-.076-.337-.076-.75V17q0-2.25 2.25-2.25H16q2.25 0 2.25 2.25v.5q0 .413-.076.75h2q.076-.337.076-.75zm-4.25 7H3.786q-.036.232-.036.5q0 2 2 2h12.5q2 0 2-2q0-.268-.036-.5z");
}

</style>
