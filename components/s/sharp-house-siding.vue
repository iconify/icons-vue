<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhtwx-qnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-house-siding" /></template>
<style>
.lhtwx-qnt {
  fill: currentColor;
  d: path("M19 12h3L12 3L2 12h3v8h2v-2h10v2h2zM7.21 10h9.58l.21.19V12H7v-1.81zm7.36-2H9.43L12 5.69zM7 16v-2h10v2z");
}

</style>
