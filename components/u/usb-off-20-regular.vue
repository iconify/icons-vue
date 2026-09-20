<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6q513b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-off-20-regular" /></template>
<style>
.x6q513b8n {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.707l-5.843-5.843l-.467.416a1 1 0 0 0-.336.748v1.891A1.999 1.999 0 1 1 8 17a2 2 0 0 1 1.493-1.934a1 1 0 0 0-.329-.64L5.671 11.32A2 2 0 0 1 5 9.826v-.914a1.498 1.498 0 0 1 .307-2.898l-3.16-3.16a.5.5 0 0 1 0-.708m4.84 5.546A1.5 1.5 0 0 1 6 8.912v.914a1 1 0 0 0 .336.748L9.5 13.386v-3.179zm3.514 3.694l.094-.085l-.094-.094zM15.5 4a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H15v.826c0 .571-.244 1.116-.67 1.495L12.8 10.68l-.708-.708l1.572-1.397c.213-.19.336-.462.336-.748V7h-.5a.5.5 0 0 1-.5-.5v-2a.5.5 0 0 1 .5-.5zM9.575 1.235a.5.5 0 0 1 .849 0l1.249 2.004a.5.5 0 0 1-.424.765H10.5v4.375l-1-1V4.004h-.75a.5.5 0 0 1-.424-.765z");
}

</style>
