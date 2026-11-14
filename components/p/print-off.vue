<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ho8hnx60j"/><path class="m9ydrob-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:print-off" /></template>
<style>
.ho8hnx60j {
  d: path("M10.014 14H7v3H5.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T3.5 15v-5q0-.124.015-.248q.016-.123.046-.244q.031-.12.076-.236q.046-.116.105-.226q.059-.109.132-.21q.072-.101.156-.193q.085-.091.18-.171t.199-.148M11.943 8H18.5q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v5q0 .308-.092.601q-.093.293-.269.545M7.569 3.598Q7.773 3.5 8 3.5h8q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T17 4.5V8");
}

.m9ydrob-a {
  d: path("M16.6 20.5H7V14h3.1M3.5 3.5l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
