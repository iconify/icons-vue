<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsv9o4b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:texture-minus-outline" /></template>
<style>
.wsv9o4b0p {
  fill: currentColor;
  d: path("M4.4 21q-.475-.1-.888-.513T3 19.6L19.6 3q.525.125.9.513t.525.887zm4.9 0l2.7-2.7V21zm4.7-2v-2h8v2zM3 14.7v-2.8L11.9 3h2.8zm12.3.3L21 9.3v2.8L18.1 15zM3 7V5q0-.825.588-1.412T5 3h2z");
}

</style>
