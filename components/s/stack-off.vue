<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-y3rqj7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stack-off" /></template>
<style>
.g-y3rqj7c {
  fill: currentColor;
  d: path("M21 18.189L11.812 9h7.573q.67 0 1.143.472q.472.472.472 1.144zM14 6.616v-2q0-.25-.183-.433T13.385 4H6.812l-1-1h7.573q.67 0 1.143.472q.472.472.472 1.144v2zm6.287 15.098L19.573 21h-8.958q-.696 0-1.156-.46T9 19.386v-8.958l-5-5V14h2.616v1h-2q-.697 0-1.156-.46Q3 14.08 3 13.386V4.427l-.713-.713L3 3l18 18z");
}

</style>
