<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0wljubgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moon-full" /></template>
<style>
.d0wljubgk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001-4.039 2.855-6.896T12 2.247t6.895 2.857T21.75 12q.001 4.039-2.855 6.896T12 21.753q-4.04 0-6.895-2.857Q2.249 16.039 2.25 12M9.5 6.25q-3.25 0-3.25 3.25t3.25 3.25t3.25-3.25T9.5 6.25M12.25 15q0 2.25 2.25 2.25T16.75 15t-2.25-2.25T12.25 15");
}

</style>
