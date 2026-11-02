<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m9rrolbsn"/><path class="s8cp5abrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m9rrolbsn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 19v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-4c0-.155.036-.308.106-.447l1-2C4.643 8.478 5.652 7.001 7 7h10c1.348.001 2.357 1.478 2.894 2.553l1 2c.07.139.106.292.106.447v4c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1Zm9.382-8l-.724-1.447A1 1 0 0 0 16.764 9H7.236a1 1 0 0 0-.894.553L5.618 11Z");
}

.s8cp5abrj {
  d: path("M14 6h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2M3 13a1 1 0 0 1 0-2h.382l.724-1.447C4.643 8.478 5.652 7.001 7 7h10c1.348.001 2.357 1.478 2.894 2.553L20.618 11H21a1 1 0 0 1 0 2Zm15.382-2l-.276-.553c-.216-.431-.47-.857-.813-1.2c-.093-.093-.2-.197-.324-.247H7.031c-.124.05-.231.154-.324.247c-.343.343-.597.769-.813 1.2L5.618 11ZM8 14h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

</style>
