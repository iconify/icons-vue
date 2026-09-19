<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evgrg-a9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-person-add-alt-1" /></template>
<style>
.evgrg-a9i {
  fill: currentColor;
  d: path("M13 8c0-2.21-1.79-4-4-4S5 5.79 5 8s1.79 4 4 4s4-1.79 4-4m2 2v2h3v3h2v-3h3v-2h-3V7h-2v3zM1 18v2h16v-2c0-2.66-5.33-4-8-4s-8 1.34-8 4");
}

</style>
