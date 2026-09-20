<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-m9n10-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-star-24-filled" /></template>
<style>
.a-m9n10-m {
  fill: currentColor;
  d: path("m17 21.245l.002-6A7.97 7.97 0 0 1 12 17a7.97 7.97 0 0 1-5-1.754l.003 6a.75.75 0 0 0 1.181.612l3.817-2.687l3.818 2.687a.75.75 0 0 0 1.182-.613M19 9A7 7 0 1 0 5 9a7 7 0 0 0 14 0m-6.771-3.358l.912 1.853l2.044.295c.21.03.293.288.142.435l-1.479 1.44l.35 2.036a.255.255 0 0 1-.37.269L12 11.008l-1.827.962a.255.255 0 0 1-.37-.269l.35-2.035l-1.48-1.44a.255.255 0 0 1 .142-.436l2.044-.295l.912-1.853a.255.255 0 0 1 .458 0");
}

</style>
