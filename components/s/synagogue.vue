<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj190u2ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:synagogue" /></template>
<style>
.xj190u2ug {
  fill: currentColor;
  d: path("M17.962 8.5V7.27q0-.884.558-1.442q.559-.559 1.442-.559t1.441.559t.559 1.441V8.5zm-15.923 0V7.27q0-.884.558-1.442q.559-.559 1.442-.559t1.44.559q.56.558.56 1.441V8.5zm0 11.462V9.269h4v10.693zm4.769 0V8.808L12 4.366l5.192 4.442v11.154h-3.5V16q0-.748-.472-1.22T12 14.308t-1.22.472t-.472 1.22v3.962zm11.154 0V9.269h4v10.693zm-5.169-9.169q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323");
}

</style>
