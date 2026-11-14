<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex2uaytfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:play" /></template>
<style>
.ex2uaytfc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.444 5.954l5.005 3.203q1.556.996 1.556 2.843t-1.556 2.843l-5.005 3.203q-1.685 1.078-3.439.118T6.25 15.203V8.797q0-2 1.755-2.961t3.439.118");
}

</style>
