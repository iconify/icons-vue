<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi15-nbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tennis-ball-can" /></template>
<style>
.pi15-nbvk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 8q0-1.34-1.721-2.027q-.706-1.694-2.67-1.989q-1.74-.261-2.859.818q-1.119-1.079-2.859-.818q-1.964.295-2.67 1.989Q4.75 6.66 4.75 8v11.5q0 2.75 7.25 2.75t7.25-2.75zm-1.5 5.5q0 1.25-5.75 1.25T6.25 13.5V9.933q1.798.817 5.75.817t5.75-.817zm-11.5 1.933q1.798.817 5.75.817t5.75-.817V19.5q0 1.25-5.75 1.25T6.25 19.5z");
}

</style>
