<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgmuuobrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:post-workout" /></template>
<style>
.tgmuuobrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.232 20.5q-.065.113-.145.217t-.173.197t-.196.173t-.218.145q-.113.066-.235.116t-.247.084q-.127.034-.257.051t-.261.017h-5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4.5 19.5V10L7 7.5v-2h4v2l2.5 2.5v5.464M8.5 2.5h1A1.5 1.5 0 0 1 11 4a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 7 4a1.5 1.5 0 0 1 1.5-1.5M14.75 18l2 2L21 15.75");
}

</style>
