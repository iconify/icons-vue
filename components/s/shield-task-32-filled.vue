<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mx5ycac3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-task-32-filled" /></template>
<style>
.mx5ycac3y {
  fill: currentColor;
  d: path("M15.445 2.168a1 1 0 0 1 1.11 0c2.916 1.944 6.76 3.859 11.545 4.337a1 1 0 0 1 .9.995V16c0 3.88-2.124 7.17-4.701 9.546c-2.572 2.372-5.737 3.971-8.115 4.417l-.184.034l-.184-.034c-2.378-.446-5.543-2.045-8.115-4.417C5.124 23.17 3 19.88 3 16V7.5a1 1 0 0 1 .9-.995c4.785-.478 8.63-2.393 11.545-4.337m7.262 10.54a1 1 0 0 0-1.414-1.415L14 18.586l-2.293-2.293a1 1 0 0 0-1.414 1.414l3 3a1 1 0 0 0 1.414 0z");
}

</style>
