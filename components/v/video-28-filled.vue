<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="o_2409bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-28-filled" /></template>
<style>
.o_2409bve {
  fill: currentColor;
  d: path("M2 9.75A3.75 3.75 0 0 1 5.75 6h8.5A3.75 3.75 0 0 1 18 9.75v8.5A3.75 3.75 0 0 1 14.25 22h-8.5A3.75 3.75 0 0 1 2 18.25zm21.252 10.933L19 17.747V10.25l4.252-2.936c1.16-.802 2.744.03 2.744 1.44v10.49c0 1.41-1.583 2.241-2.744 1.44");
}

</style>
