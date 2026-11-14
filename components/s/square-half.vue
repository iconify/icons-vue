<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrhwhdtsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:square-half" /></template>
<style>
.nrhwhdtsn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.75h6.5q2.75 0 2.75 2.75v13q0 2.75-2.75 2.75h-13q-2.75 0-2.75-2.75v-13q0-1.139.805-1.945q.806-.805 1.945-.805zm.75 17h5.75q1.25 0 1.25-1.25v-13q0-1.25-1.25-1.25h-5.75z");
}

</style>
