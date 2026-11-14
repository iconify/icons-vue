<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6-kdqbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:zen-mode" /></template>
<style>
.t6-kdqbld {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 4.75Q8.75 1.5 12 1.5q1.346 0 2.298.952t.952 2.298Q15.25 8 12 8T8.75 4.75m-1.021 5.96l-3.741 3.492q-.109.101-.171.237q-.061.136-.067.285q-.005.149.048.289q.052.14.154.249q.05.054.11.097t.127.074q.068.03.139.047t.146.02t.147-.01t.142-.038t.132-.064t.117-.09l3.75-3.5l.018-.018q1.031-1.03 3.22-1.03t3.22 1.03l.018.018l3.75 3.5q.109.102.249.154t.289.048q.149-.006.285-.067t.237-.171q.051-.054.09-.117q.038-.063.064-.132t.038-.142t.01-.147q-.003-.074-.02-.146q-.017-.071-.047-.139q-.031-.067-.074-.127t-.097-.11l-3.741-3.492Q14.802 9.25 12 9.25t-4.271 1.46M1.75 19.5q0-2.75 3.25-2.75q.105 0 .206.029L12 18.72l6.794-1.941q.101-.029.206-.029q3.25 0 3.25 2.75q0 2.25-2.75 2.25h-15q-2.75 0-2.75-2.25");
}

</style>
