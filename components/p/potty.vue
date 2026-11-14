<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7ex42bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:potty" /></template>
<style>
.r7ex42bhj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 5.25v3.317q-2 .749-2 2.183q0 1.057 1.086 1.742q.565 3.79 3.071 5.373q-.657.489-.657 1.635q0 2 2 2h6.5q2 0 2-2q0-1.146-.657-1.635q2.506-1.583 3.071-5.373q1.086-.685 1.086-1.742q0-1.434-2-2.183V5.25q0-2.75-2.75-2.75H8q-2.75 0-2.75 2.75M12 7.75q-3.216 0-5.25.405V5.25Q6.75 4 8 4h8q1.25 0 1.25 1.25v2.905Q15.216 7.75 12 7.75m5.996 5.422Q16.889 17.5 12 17.5t-5.996-4.328q2.155.578 5.996.578t5.996-.578");
}

</style>
