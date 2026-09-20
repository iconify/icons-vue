<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iu2tfx4av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:radio-button-off-16-regular" /></template>
<style>
.iu2tfx4av {
  fill: currentColor;
  d: path("m1.853 1.147l13 13a.5.5 0 0 1-.707.707l-2.272-2.272a6 6 0 0 1-8.456-8.456L1.146 1.854a.5.5 0 0 1 .707-.707M3 8a5 5 0 0 0 5 5h-.001a4.98 4.98 0 0 0 3.164-1.129L4.128 4.836A4.98 4.98 0 0 0 3 8m10 0a5 5 0 0 0-5-5l-.002-.002a4.94 4.94 0 0 0-2.295.583l-.747-.747A5.97 5.97 0 0 1 8 2a6 6 0 0 1 6 6c0 1.112-.308 2.15-.835 3.043l-.747-.747A4.94 4.94 0 0 0 13 8");
}

</style>
