<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1_sqj9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:play-square" /></template>
<style>
.nr1_sqj9a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75m-1.667 6.584l1.206.768q1.041.664 1.041 1.898t-1.041 1.898l-1.206.768q-1.124.714-2.291.073T9.25 12.767v-1.534q0-1.331 1.167-1.972t2.29.073z");
}

</style>
