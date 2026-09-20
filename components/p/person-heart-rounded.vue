<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvlcjebdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-heart-rounded" /></template>
<style>
.vvlcjebdw {
  fill: currentColor;
  d: path("M9.877 10.508Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m-3.839 8.108q-.44 0-.739-.3Q5 18.017 5 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.193-.567 2.383-.901q1.189-.333 2.385-.42q.268-.03.444.175q.177.206.149.498q-.007.029-.007.055v.055q0 .769.263 1.506t.932 1.407l.092.087q.321.32.155.75t-.649.43zm10.931-.566l-2.396-2.396q-.287-.287-.395-.594q-.109-.308-.109-.626q0-.684.479-1.213t1.244-.529q.604 0 .946.277t.797.731q.442-.442.787-.725t.955-.283q.79 0 1.257.532T21 14.441q0 .317-.121.634t-.383.579L18.1 18.05q-.242.242-.565.242t-.566-.242");
}

</style>
