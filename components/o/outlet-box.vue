<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc5y4wbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:outlet-box" /></template>
<style>
.mc5y4wbez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75M10.5 6.25h3q1.76 0 3.005 1.245T17.75 10.5v3q0 1.76-1.245 3.005T13.5 17.75h-3q-1.76 0-3.005-1.245T6.25 13.5v-3q0-1.76 1.245-3.005T10.5 6.25");
}

</style>
