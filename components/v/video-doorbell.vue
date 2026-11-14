<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-4tvm5qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-doorbell" /></template>
<style>
.b-4tvm5qw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.066 3.434Q14.382 1.75 12 1.75T7.934 3.434T6.25 7.5v9q0 2.382 1.684 4.066T12 22.25t4.066-1.684T17.75 16.5v-9q0-2.382-1.684-4.066M8.75 8q0-3.25 3.25-3.25T15.25 8T12 11.25T8.75 8m.5 7.75Q9.25 13 12 13t2.75 2.75T12 18.5t-2.75-2.75");
}

</style>
