<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-nx_4usz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-outline" /></template>
<style>
.m-nx_4usz {
  fill: currentColor;
  d: path("M11.952 15.616q.729-.041 1.064-.524l5.253-7.323l-7.361 5.216q-.502.334-.559 1.038t.409 1.17t1.194.423M12 5q1.379 0 2.51.336q1.132.335 2.256 1.025l-.92.623q-.883-.482-1.828-.733T12 6Q8.675 6 6.337 8.338T4 14q0 1.05.288 2.075T5.1 18h13.8q.575-.95.838-1.975T20 13.9q0-.9-.232-1.894t-.734-1.852l.624-.92q.73 1.252 1.033 2.356T21 13.888q.006 1.29-.287 2.408q-.292 1.118-.91 2.254q-.12.2-.365.325T18.9 19H5.1q-.275 0-.51-.134q-.234-.135-.394-.393q-.496-.875-.846-1.974T3 14q0-1.844.701-3.484t1.91-2.867T8.47 5.71Q10.123 5 12 5m.04 6.96");
}

</style>
