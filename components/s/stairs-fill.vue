<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hosk2tlna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stairs-fill" /></template>
<style>
.hosk2tlna {
  fill: currentColor;
  d: path("M12 22L4 22C2.3431 22 1 20.6569 1 19L1 16C1 14.8954 1.8954 14 3 14L7 14L7 10C7 8.8954 7.8954 8 9 8L13 8L13 4C13 2.8954 13.8954 2 15 2L20 2C21.6569 2 23 3.3431 23 5L23 19C23 20.6569 21.6569 22 20 22Z");
}

</style>
