<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hesk4iebv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-connected-no-internet-4-bar-outline" /></template>
<style>
.hesk4iebv {
  fill: currentColor;
  d: path("M2 22L22 2v6h-4v14zm18.288-.288Q20 21.426 20 21t.288-.712T21 20t.713.288T22 21t-.288.713T21 22t-.712-.288M20 18v-8h2v8z");
}

</style>
