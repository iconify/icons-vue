<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si0zvsbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-alt-off" /></template>
<style>
.si0zvsbkd {
  fill: currentColor;
  d: path("m19.833 21.26l-6.41-6.41V19h-1.615v-5.765L2.74 4.167l.713-.713l17.092 17.092zM19 16.189l-1.616-1.616V5H19zM6 19v-4h1.616v4z");
}

</style>
