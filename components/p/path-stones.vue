<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r79pekgnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:path-stones" /></template>
<style>
.r79pekgnb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 5.5q0-2.75 3.75-2.75q1.47 0 2.537.712Q14 4.27 14 5.5t-1.213 2.038q-1.067.712-2.537.712q-3.75 0-3.75-2.75M16.25 9q-4.5 0-4.5 3t4.5 3t4.5-3t-4.5-3M3 18.5q0-1.56 1.677-2.585Q6.175 15 8.25 15q5.25 0 5.25 3.5T8.25 22q-2.075 0-3.573-.915Q3 20.06 3 18.5");
}

</style>
