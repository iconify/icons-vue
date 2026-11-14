<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9xk84b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:microplate" /></template>
<style>
.n9xk84b9w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 3.75h-14q-.149 0-.287.057t-.243.163l-3 3q-.106.105-.163.243T1.75 7.5v10q0 2.75 2.75 2.75h15q2.75 0 2.75-2.75v-11q0-2.75-2.75-2.75m-13 6q-.75 0-.75-.75t.75-.75t.75.75t-.75.75M4.25 9q0-2.25 2.25-2.25T8.75 9T6.5 11.25T4.25 9m7.75.75q-.75 0-.75-.75t.75-.75t.75.75t-.75.75M9.75 9q0-2.25 2.25-2.25T14.25 9T12 11.25T9.75 9m7.75.75q-.75 0-.75-.75t.75-.75t.75.75t-.75.75M15.25 9q0-2.25 2.25-2.25T19.75 9t-2.25 2.25T15.25 9M6.5 15.75q-.75 0-.75-.75t.75-.75t.75.75t-.75.75M4.25 15q0-2.25 2.25-2.25T8.75 15T6.5 17.25T4.25 15m7.75.75q-.75 0-.75-.75t.75-.75t.75.75t-.75.75M9.75 15q0-2.25 2.25-2.25T14.25 15T12 17.25T9.75 15m7.75.75q-.75 0-.75-.75t.75-.75t.75.75t-.75.75M15.25 15q0-2.25 2.25-2.25T19.75 15t-2.25 2.25T15.25 15");
}

</style>
