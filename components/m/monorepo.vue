<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs53e3bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:monorepo" /></template>
<style>
.xs53e3bea {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 6q0-1.139.805-1.945q.806-.805 1.945-.805H9q.149 0 .287.057t.243.163l1.781 1.78H19.5q2.75 0 2.75 2.75v10.5q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75zm9.5 4.25Q11.25 8 9 8t-2.25 2.25T9 12.5t2.25-2.25M15 8q-2.25 0-2.25 2.25T15 12.5t2.25-2.25T15 8m-3.75 8q0-2.25-2.25-2.25T6.75 16T9 18.25T11.25 16M15 13.75q-2.25 0-2.25 2.25T15 18.25T17.25 16T15 13.75");
}

</style>
