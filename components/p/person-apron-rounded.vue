<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxj7dhb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-apron-rounded" /></template>
<style>
.fxj7dhb6v {
  fill: currentColor;
  d: path("M9.877 10.508Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m5.546 8.108v-4.497q.585.18 1.147.39q.561.211 1.1.464q.596.298.963.833T19 16.977v.6q0 .44-.299.74q-.299.299-.74.299zm-5.846-2.5V13.88q.606-.133 1.211-.2T12 13.617t1.212.066t1.211.199v2.235zM5 17.577v-.6q0-.637.367-1.171t.964-.833q.538-.253 1.1-.463q.561-.211 1.146-.39v4.496H6.039q-.441 0-.74-.3Q5 18.017 5 17.577");
}

</style>
