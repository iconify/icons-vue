<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":89};
const content = `<path class="wxfphbccg"/><path class="a14dgugjc"/><path class="rz7kzwb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:visual-website-optimizer" /></template>
<style>
.a14dgugjc {
  d: path("M165.647 0h45.177l-60.236 88.086L128 55.054l-22.588 33.032l-22.843-33.405l3.572-5.362l19.27 28.18l17.577-25.703L128 44.467l5.012 7.33l17.576 25.702l48.98-71.627h-84.486L118.993 0h46.654z");
  fill: var(--svg-color--802050, #802050);
}

.rz7kzwb1j {
  d: path("M60.235 88.086L0 0h120.47L60.236 88.086zm0-10.587l48.98-71.627h-97.96L60.235 77.5z");
  fill: var(--svg-color--26134d, #26134D);
}

.wxfphbccg {
  d: path("M210.824 0C235.774 0 256 19.719 256 44.043c0 24.324-20.226 44.043-45.176 44.043c-21.015 0-38.679-13.989-43.728-32.936l4.005 2.536l2.077-3.118c4.686 15.962 19.766 27.646 37.646 27.646c21.623 0 39.152-17.09 39.152-38.171s-17.529-38.17-39.152-38.17c-1.851 0-3.672.125-5.454.367l3.786-5.684l-.777-.493c.81-.042 1.624-.063 2.445-.063z");
  fill: var(--svg-color--bf3078, #BF3078);
}

</style>
