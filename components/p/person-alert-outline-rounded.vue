<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trfnz1grm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-alert-outline-rounded" /></template>
<style>
.trfnz1grm {
  fill: currentColor;
  d: path("M19.48 10.52q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.163-3.164Q19.5 7.213 19.5 7V4q0-.213.144-.356t.357-.144t.356.144T20.5 4v3q0 .213-.144.356t-.357.144t-.356-.144M6.877 10.508Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739m1 .039h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.545-.916T9 14.616t-2.646.318t-2.546.916q-.38.202-.593.494Q3 16.637 3 16.97zm7.413-7.819Q11 9.21 11 8.385t-.587-1.413T9 6.385t-1.412.587T7 8.385t.588 1.412T9 10.385t1.413-.588M9 17.616");
}

</style>
