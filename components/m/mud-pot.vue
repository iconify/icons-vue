<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y10p3tu6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mud-pot" /></template>
<style>
.y10p3tu6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 5.5q0-3.25 3.25-3.25t3.25 3.25t-3.25 3.25t-3.25-3.25m-3.75.25q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75T8.5 5.75M1.75 17q0-2.064 3.257-3.349Q7.922 12.5 12 12.5t6.993 1.151Q22.25 14.936 22.25 17t-3.257 3.349Q16.078 21.5 12 21.5t-6.993-1.151Q1.75 19.064 1.75 17");
}

</style>
