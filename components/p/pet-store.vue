<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfu5y6fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-store" /></template>
<style>
.mjfu5y6fo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022zM12 10.75q-2 0-2 2q0 1.384.958 1.81q-.859.107-1.489.404q.031-.217.031-.464q0-2-2-2t-2 2t2 2q.279 0 .519-.039Q7.75 17.12 7.75 18q0 3.5 4.25 3.5t4.25-3.5q0-.863-.433-1.571q.306.071.683.071q2 0 2-2t-2-2t-2 2q0 .394.077.71q-.724-.462-1.597-.623Q14 14.178 14 12.75q0-2-2-2");
}

</style>
