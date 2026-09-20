<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8iaieban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:synagogue-rounded" /></template>
<style>
.d8iaieban {
  fill: currentColor;
  d: path("M17.962 8.5V7.27q0-.884.558-1.442q.559-.559 1.442-.559t1.441.559t.559 1.441V8.5zm-15.923 0V7.27q0-.884.558-1.442q.559-.559 1.442-.559t1.44.559q.56.558.56 1.441V8.5zm0 10.462V9.269h4v10.693h-3q-.402 0-.701-.3t-.3-.7m4.77 1V8.808L11.36 4.92q.14-.129.302-.186q.161-.058.338-.058t.339.058t.302.186l4.551 3.887v11.154H14.5q-.348 0-.578-.23t-.23-.578V16q0-.748-.472-1.22T12 14.308t-1.22.472t-.472 1.22v3.154q0 .348-.23.578t-.578.23zm11.154 0V9.269h4v9.693q0 .402-.3.7t-.7.3zm-5.169-9.169q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323");
}

</style>
