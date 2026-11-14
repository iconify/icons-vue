<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nly9ushkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:triangle-rounded" /></template>
<style>
.nly9ushkk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.602 5.622Q10.694 3.75 12 3.75t2.398 1.872l6.007 10.762q1.088 1.866.43 2.994Q20.181 20.5 18 20.5H6q-2.181 0-2.835-1.122q-.658-1.128.437-3.006L9.595 5.634z");
}

</style>
