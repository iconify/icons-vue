<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h2oof4g-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-smoking-20-regular" /></template>
<style>
.h2oof4g-j {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m.707 8H14.5a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H8.707l-3.291 3.291a7 7 0 0 0 9.875-9.875zM10 3a7 7 0 0 0-5.291 11.584L7.293 12H7v-2h2.293l5.291-5.291A6.97 6.97 0 0 0 10 3m-4 9h-.5a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5H6zm0-6.364c0-.159.213-.21.284-.068l.394.787A1 1 0 0 1 6.49 7.51l-.197.197A1 1 0 0 0 6 8.414v1.027c0 .264-.356.348-.474.112l-.407-.816a1.57 1.57 0 0 1 .532-2.005a.78.78 0 0 0 .349-.65z");
}

</style>
