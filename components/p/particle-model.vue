<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3tr6vbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:particle-model" /></template>
<style>
.q3tr6vbpp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 4.5q0-2.75 2.75-2.75T7.25 4.5T4.5 7.25T1.75 4.5M12 1.75q-2.75 0-2.75 2.75T12 7.25t2.75-2.75T12 1.75m4.75 2.75q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75M4.5 9.25q-2.75 0-2.75 2.75t2.75 2.75T7.25 12T4.5 9.25M9.25 12q0-2.75 2.75-2.75T14.75 12T12 14.75T9.25 12M19.5 9.25q-2.75 0-2.75 2.75t2.75 2.75T22.25 12T19.5 9.25M1.75 19.5q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75M12 16.75q-2.75 0-2.75 2.75T12 22.25t2.75-2.75T12 16.75m4.75 2.75q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75");
}

</style>
