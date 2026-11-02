<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y52rfeb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-fill-round" /></template>
<style>
.y52rfeb1i {
  fill: currentColor;
  d: path("M15.382 18H8.618l-1.724 3.447a1 1 0 1 1-1.788-.894l1.305-2.611A3 3 0 0 1 4 15V8c0-1.317.335-2.748 1.293-3.707l1-1C7.252 2.335 8.683 2 10 2h4c1.317 0 2.748.335 3.707 1.293l1 1C19.665 5.252 20 6.683 20 8v7a3 3 0 0 1-2.411 2.942l1.305 2.611a1 1 0 1 1-1.788.894ZM6 7.657V9h12V7.657c0-.794-.315-1.556-.875-2.118l-.004-.003l-.659-.66A3 3 0 0 0 14.343 4H9.657c-.795 0-1.557.315-2.119.876l-.002.003l-.66.659A3 3 0 0 0 6 7.657M9.01 13H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m6 0H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
