<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u12kfabbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-shield-sharp" /></template>
<style>
.u12kfabbm {
  fill: currentColor;
  d: path("M17.692 21q-1.517-.373-2.412-1.683t-.895-2.901v-2.127l3.307-1.673L21 14.288v2.127q0 1.593-.895 2.902q-.896 1.31-2.413 1.683M5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34v2.8q0 .574.082 1.122t.27 1.079zm4.877-8.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877");
}

</style>
