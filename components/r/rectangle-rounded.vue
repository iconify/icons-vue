<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhh-neolc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rectangle-rounded" /></template>
<style>
.dhh-neolc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 4.75h6q3.003 0 5.127 2.123T22.25 12t-2.123 5.127Q18.003 19.25 15 19.25H9q-3.003 0-5.127-2.123T1.75 12t2.123-5.127Q5.997 4.75 9 4.75");
}

</style>
