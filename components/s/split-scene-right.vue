<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibv72hd4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-right" /></template>
<style>
.ibv72hd4g {
  fill: currentColor;
  d: path("M5.616 19q-.691 0-1.153-.462T4 17.384V6.616q0-.691.463-1.153T5.616 5h3.5v14zm5.884 2V3h1v2h5.885q.69 0 1.152.463T20 6.616v10.769q0 .69-.463 1.153T18.385 19H12.5v2z");
}

</style>
