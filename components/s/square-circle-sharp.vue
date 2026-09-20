<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6gse8brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:square-circle-sharp" /></template>
<style>
.z6gse8brn {
  fill: currentColor;
  d: path("M8.192 15.808h7.616V8.192H8.192zm.302 4.491q-1.642-.701-2.867-1.926t-1.926-2.866T3 12.003t.701-3.508t1.926-2.857T8.493 3.71T11.998 3t3.509.709t2.859 1.922t1.925 2.857t.709 3.509t-.71 3.509t-1.926 2.867t-2.856 1.926t-3.506.701t-3.508-.701");
}

</style>
