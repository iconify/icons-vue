<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1ctqd8ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-sharp" /></template>
<style>
.a1ctqd8ji {
  fill: currentColor;
  d: path("M7 7.846v-3.23h10v3.23zm10.616 4.27q.425 0 .712-.288t.288-.712t-.288-.713t-.712-.288t-.713.288t-.287.713t.287.712t.713.288M8 19h8v-4.538H8zm-1 1v-4H3.577V8.616h16.846V16H17v4z");
}

</style>
