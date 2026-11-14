<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="askd14b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wall-outlet" /></template>
<style>
.askd14b0w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2.25h4q3.21 0 5.48 2.27T21.75 10v4q0 3.21-2.27 5.48T14 21.75h-4q-3.21 0-5.48-2.27T2.25 14v-4q0-3.21 2.27-5.48T10 2.25m-1 7.5q-2.25 0-2.25 2.25T9 14.25T11.25 12T9 9.75M12.75 12q0 2.25 2.25 2.25T17.25 12T15 9.75T12.75 12");
}

</style>
