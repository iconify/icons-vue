<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f51axpbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pentagon" /></template>
<style>
.f51axpbuv {
  fill: currentColor;
  d: path("m2 9l4 12h12l4-12l-10-7z");
}

</style>
