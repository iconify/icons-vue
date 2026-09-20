<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q18lqeban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-actors" /></template>
<style>
.q18lqeban {
  fill: currentColor;
  d: path("M3.962 18q-.98 0-1.586-.607t-.607-1.585V8.192q0-.979.607-1.585T3.962 6h7.615q.979 0 1.586.607t.606 1.585v7.616q0 .979-.606 1.585T11.577 18zm-1.193-2.573q1.1-.708 2.35-1.106t2.65-.398t2.65.398t2.35 1.106V8.192q0-.5-.346-.846T11.577 7H3.962q-.5 0-.846.346q-.347.346-.347.846zm3.272-3.198q-.714-.713-.714-1.729t.714-1.729t1.728-.713t1.729.713q.714.713.714 1.729t-.714 1.729t-1.729.713t-1.728-.713M17 18V6h1v12zm4.23 0V6h1v12z");
}

</style>
