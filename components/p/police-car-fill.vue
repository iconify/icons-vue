<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh3_fmlur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-fill" /></template>
<style>
.kh3_fmlur {
  fill: currentColor;
  d: path("M8 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm9 0a1 1 0 0 1 0 2h-1a1 1 0 0 1 0-2Zm-3 2v1h3c1.348.001 2.357 1.478 2.894 2.553L20.618 11H21a1 1 0 0 1 0 2v3c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-3a1 1 0 0 1 0-2h.382l.724-1.447C4.643 8.478 5.652 7.001 7 7h3V6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1m2.764 3H7.236a1 1 0 0 0-.894.553L5.618 11h12.764l-.724-1.447A1 1 0 0 0 16.764 9M8 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
