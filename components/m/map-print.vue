<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u51qekbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-print" /></template>
<style>
.u51qekbrv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1.75H6.5q-2.75 0-2.75 2.75v15q0 2.75 2.75 2.75h11q2.75 0 2.75-2.75V8q0-.149-.057-.287t-.163-.243l-5.5-5.5q-.105-.106-.243-.163T14 1.75M7.263 9.788l3-1q.115-.038.237-.038t.237.038l2.763.921l2.763-.921q.141-.047.29-.036q.149.01.282.077q.134.067.232.18q.097.112.145.254q.038.115.038.237v7q0 .059-.009.117t-.027.113q-.018.056-.045.109q-.026.052-.061.1q-.034.047-.075.089t-.089.076t-.099.062t-.108.046l-2.999.999l-.001.001q-.115.038-.237.038t-.237-.038l-.001-.001l-2.762-.92l-2.763.921q-.141.047-.29.036q-.149-.01-.282-.077q-.134-.067-.232-.18q-.097-.112-.145-.254q-.038-.115-.038-.237v-7q0-.059.009-.117t.027-.113q.018-.056.045-.109q.026-.052.061-.1q.034-.047.075-.089t.089-.076q.047-.035.099-.062t.108-.046");
}

</style>
