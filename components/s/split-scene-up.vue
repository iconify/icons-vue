<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfiw6-bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-up" /></template>
<style>
.vfiw6-bmw {
  fill: currentColor;
  d: path("M6.616 20q-.691 0-1.153-.462T5 18.384v-3.5h14v3.5q0 .691-.462 1.153T17.384 20zM3 12.5v-1h2V5.616q0-.691.463-1.153T6.616 4h10.769q.69 0 1.153.463T19 5.616V11.5h2v1z");
}

</style>
