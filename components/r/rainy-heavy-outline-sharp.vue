<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4dxmqybd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rainy-heavy-outline-sharp" /></template>
<style>
.t4dxmqybd {
  fill: currentColor;
  d: path("M7.78 18.677L1.324 5.781l.896-.452l6.458 12.885zm4.657 0L5.998 5.781l.896-.458l6.452 12.89zm4.675 0L10.673 5.781l.89-.458l6.439 12.871zm4.669-.006l-6.452-12.89l.89-.458l6.458 12.896z");
}

</style>
