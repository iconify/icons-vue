<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y40sji63w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rectangle" /></template>
<style>
.y40sji63w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 4.75h12q1.76 0 3.005 1.245T22.25 9v6q0 1.76-1.245 3.005T18 19.25H6q-1.76 0-3.005-1.245T1.75 15V9q0-1.76 1.245-3.005T6 4.75");
}

</style>
