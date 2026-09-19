<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="smxip0nhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pillars" /></template>
<style>
.smxip0nhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.646 2.508c-11.824-.322-21.597 9.04-21.827 20.91c-.23 11.869 9.168 21.752 20.993 22.074c10.284.28 19.258-6.82 21.373-16.912c-6.387 7.227-17.245 8.116-24.252 1.984s-7.509-16.96-1.121-24.187a18.1 18.1 0 0 1 4.834-3.869");
}

</style>
