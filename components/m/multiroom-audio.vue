<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfj_yi55k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:multiroom-audio" /></template>
<style>
.vfj_yi55k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 3.25h-2.75q-3.375 0-3.375 3.375v10.75q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375V6.625q0-3.375-3.375-3.375m8.25 0h2.75q3.375 0 3.375 3.375v10.75q0 3.375-3.375 3.375h-2.75q-3.375 0-3.375-3.375V6.625q0-3.375 3.375-3.375M6.5 11.75q2.75 0 2.75 2.75T6.5 17.25T3.75 14.5t2.75-2.75m8.25 2.75q0 2.75 2.75 2.75t2.75-2.75t-2.75-2.75t-2.75 2.75");
}

</style>
