<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5v2iccdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:progress-25" /></template>
<style>
.z5v2iccdy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 8.25H3.5q-1.75 0-1.75 1.75v4q0 1.75 1.75 1.75h16.25q1.036 0 1.768-.732t.732-1.768v-2.5q0-1.036-.732-1.768T19.75 8.25");
}

</style>
