<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="y9lp_ob0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:receipt-28-filled" /></template>
<style>
.y9lp_ob0x {
  fill: currentColor;
  d: path("M3 5.75A2.75 2.75 0 0 1 5.75 3h11.5A2.75 2.75 0 0 1 20 5.75V17h5v4.25A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25zM20 23.5h1.25a2.25 2.25 0 0 0 2.25-2.25V18.5H20zM7 8.75c0 .414.336.75.75.75h7.5a.75.75 0 0 0 0-1.5h-7.5a.75.75 0 0 0-.75.75M7.75 13a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zM7 18.75c0 .414.336.75.75.75h3.5a.75.75 0 0 0 0-1.5h-3.5a.75.75 0 0 0-.75.75");
}

</style>
