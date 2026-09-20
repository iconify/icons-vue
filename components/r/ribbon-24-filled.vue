<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riuj66k8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-24-filled" /></template>
<style>
.riuj66k8b {
  fill: currentColor;
  d: path("M17.002 15.244L17 21.245a.75.75 0 0 1-1.182.613L12 19.171l-3.817 2.687a.75.75 0 0 1-1.181-.613l-.002-6A7.97 7.97 0 0 0 12 17a7.97 7.97 0 0 0 5.002-1.756M12 2a7 7 0 1 1 0 14a7 7 0 0 1 0-14");
}

</style>
