<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la58t3bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-actors-rounded" /></template>
<style>
.la58t3bwh {
  fill: currentColor;
  d: path("M3.962 18q-.98 0-1.586-.607t-.607-1.585V8.192q0-.979.607-1.585T3.962 6h7.615q.979 0 1.586.607t.606 1.585v7.616q0 .979-.606 1.585T11.577 18zm-1.193-2.573q1.1-.708 2.35-1.106t2.65-.398t2.65.398t2.35 1.106V8.192q0-.5-.346-.846T11.577 7H3.962q-.5 0-.846.346q-.347.346-.347.846zm3.272-3.198q-.714-.713-.714-1.729t.714-1.729t1.728-.713t1.729.713q.714.713.714 1.729t-.714 1.729t-1.729.713t-1.728-.713m11.102 5.628Q17 17.714 17 17.5v-11q0-.213.143-.357T17.5 6t.357.143T18 6.5v11q0 .214-.143.357T17.5 18t-.357-.143m4.231 0q-.143-.143-.143-.357v-11q0-.213.143-.357T21.731 6t.356.143t.144.357v11q0 .214-.144.357t-.356.143t-.357-.143");
}

</style>
