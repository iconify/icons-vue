<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so3silb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-fill-round" /></template>
<style>
.so3silb3v {
  fill: currentColor;
  d: path("M14 4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2ZM9 19v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-3a1 1 0 0 1 0-2h.382l.724-1.447C4.848 8.069 6.307 7 8 7h8c1.693 0 3.152 1.069 3.894 2.553L20.618 11H21a1 1 0 0 1 0 2v3c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1Zm9.382-8l-.171-.342l-.002-.004A3 3 0 0 0 15.528 9H8.472a3 3 0 0 0-2.681 1.654L5.618 11ZM8 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
