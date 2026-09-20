<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lf4v0eb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-20-regular" /></template>
<style>
.lf4v0eb5u {
  fill: currentColor;
  d: path("M9.575 1.235a.5.5 0 0 1 .849 0l1.249 2.004a.5.5 0 0 1-.424.765H10.5v7.382l3.164-2.812c.213-.19.336-.462.336-.748V7h-.5a.5.5 0 0 1-.5-.5v-2a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H15v.826a2 2 0 0 1-.67 1.495l-3.494 3.105c-.213.19-.336.462-.336.748v1.891A1.999 1.999 0 1 1 8 17a2 2 0 0 1 1.493-1.934a1 1 0 0 0-.329-.64L5.671 11.32A2 2 0 0 1 5 9.826v-.914A1.498 1.498 0 0 1 5.5 6A1.5 1.5 0 0 1 6 8.912v.914a1 1 0 0 0 .336.748L9.5 13.386V4.004h-.749a.5.5 0 0 1-.425-.765z");
}

</style>
