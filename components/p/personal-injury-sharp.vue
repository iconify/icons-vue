<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5r9hbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:personal-injury-sharp" /></template>
<style>
.cr5r9hbvj {
  fill: currentColor;
  d: path("M9.175 8.825Q8 7.65 8 6t1.175-2.825T12 2t2.825 1.175T16 6t-1.175 2.825T12 10T9.175 8.825M9.75 20q-.325 0-.537-.213T9 19.25t.213-.537t.537-.213h1.9l-.7 1.5zM4 22v-6.775q0-.85.425-1.562T5.6 12.55q1.5-.75 3.113-1.15T12 11q.75 0 1.513.075t1.487.25L12.575 16.5H9.75q-1.15 0-1.95.8T7 19.25t.8 1.95t1.95.8zm12.95 0V11.925q.375.125.738.288t.712.337q.75.4 1.175 1.113T20 15.225V20q0 .825-.587 1.413T18 22z");
}

</style>
