<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srpy8kata"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newspaper-off" /></template>
<style>
.srpy8kata {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 20.5h11.8m3.95-3.922V5.5q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145q-.069-.07-.145-.132t-.158-.117t-.168-.101t-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T18.5 3.5H9q-.301 0-.589.089q-.288.088-.537.258M7 10.965v7.285q0 .111-.011.221t-.032.218q-.022.108-.054.214t-.074.208q-.043.102-.095.2q-.052.097-.113.189t-.132.177t-.148.164t-.164.148q-.085.07-.177.132q-.092.061-.189.113q-.098.052-.2.095q-.102.042-.208.074t-.214.054t-.218.032t-.221.011t-.221-.011t-.218-.032t-.214-.054q-.106-.032-.208-.074q-.102-.043-.2-.095q-.097-.052-.189-.113t-.177-.132t-.164-.148q-.078-.078-.148-.164q-.07-.085-.132-.177q-.061-.092-.113-.189q-.052-.098-.095-.2q-.042-.102-.074-.208t-.054-.214t-.032-.218t-.011-.221V10h3.601M11.5 7H17m-1.1 5H17M3.5 3.5l17 17");
}

</style>
