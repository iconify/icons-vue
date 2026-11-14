<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbt3txpvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stack-data" /></template>
<style>
.xbt3txpvy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q2.75 0 2.75 2.75T18 7.75H6Q3.25 7.75 3.25 5T6 2.25m12 7H6q-2.75 0-2.75 2.75T6 14.75h12q2.75 0 2.75-2.75T18 9.25m-12 7h12q2.75 0 2.75 2.75T18 21.75H6q-2.75 0-2.75-2.75T6 16.25");
}

</style>
