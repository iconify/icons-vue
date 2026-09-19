<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6fyrlbnb"/><path class="jm866rbkp"/><path class="slugxqbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-offline-share" /></template>
<style>
.jm866rbkp {
  fill: currentColor;
  d: path("M20 1H8v18h12zm-2 14h-8V5h8z");
}

.r6fyrlbnb {
  fill: currentColor;
  d: path("M6 5H4v18h12v-2H6z");
}

.slugxqbcm {
  fill: currentColor;
  d: path("M12.5 10.25h2V12L17 9.5L14.5 7v1.75H11V12h1.5z");
}

</style>
