<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_la0-b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-heart" /></template>
<style>
.q_la0-b7m {
  fill: currentColor;
  d: path("M9.877 10.508Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877M5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.359-.64 2.709-.98t2.711-.377h.08q-.082.205-.114.4q-.031.196-.031.419q0 .769.262 1.506t.932 1.407l1.292 1.268zm12.535 0l-2.962-2.962q-.287-.287-.395-.594q-.109-.308-.109-.626q0-.684.479-1.213t1.244-.529q.604 0 .946.277t.797.731q.442-.442.787-.725t.955-.283q.79 0 1.257.532T21 14.441q0 .317-.121.634t-.383.579z");
}

</style>
