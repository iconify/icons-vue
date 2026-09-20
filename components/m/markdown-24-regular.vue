<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5dr_bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:markdown-24-regular" /></template>
<style>
.ea5dr_bgh {
  fill: currentColor;
  d: path("M2.97 5.054a.75.75 0 0 1 .823.178L8.5 10.163l4.707-4.93a.752.752 0 0 1 1.293.517v11.5a.75.75 0 0 1-1.5 0V7.622l-3.957 4.146a.75.75 0 0 1-1.086 0L4 7.622v9.628a.75.75 0 0 1-1.5 0V5.75a.75.75 0 0 1 .47-.696M19.25 5a.75.75 0 0 1 .75.75v9.69l1.223-1.222a.75.75 0 1 1 1.06 1.06l-2.5 2.502a.75.75 0 0 1-1.061 0l-2.502-2.502a.75.75 0 0 1 1.06-1.06l1.22 1.22V5.75a.75.75 0 0 1 .75-.75");
}

</style>
