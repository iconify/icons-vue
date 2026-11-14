<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8ua7f4bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-power-outlet" /></template>
<style>
.s8ua7f4bn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75h-5q-3.21 0-5.48 2.27T1.75 9.5v5q0 3.21 2.27 5.48t5.48 2.27h5q3.21 0 5.48-2.27t2.27-5.48v-5q0-3.21-2.27-5.48T14.5 1.75m-5 8.5q1.75 0 1.75 1.75T9.5 13.75T7.75 12t1.75-1.75M12.75 12q0-1.75 1.75-1.75T16.25 12t-1.75 1.75T12.75 12");
}

</style>
