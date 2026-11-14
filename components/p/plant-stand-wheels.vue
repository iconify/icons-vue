<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmhb06adi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plant-stand-wheels" /></template>
<style>
.jmhb06adi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.729 4.25H9.271q-1.043 0-1.717.796T7.051 6.87l.75 4.5q.034.201.085.38H4.75q-2.5 0-2.5 2.5q0 2.341 2.192 2.49q-.192.534-.192 1.26q0 2.75 2.75 2.75T9.75 18q0-.719-.188-1.25h4.876q-.188.531-.188 1.25q0 2.75 2.75 2.75T19.75 18q0-.73-.194-1.267q.84-.094 1.462-.715q.732-.732.732-1.768t-.732-1.768t-1.768-.732h-3.136q.051-.179.085-.38l.75-4.499q.172-1.029-.503-1.825q-.674-.796-1.717-.796");
}

</style>
