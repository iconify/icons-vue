<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqw0w3bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-2-fill" /></template>
<style>
.dqw0w3bhf {
  fill: currentColor;
  d: path("M15 5C16.6569 5 18 6.34312 18 8V8.38184L20.1055 7.3291C21.435 6.66456 22.9996 7.63177 23 9.11816V14.8828C22.9995 16.3691 21.435 17.3354 20.1055 16.6709L18 15.6182V16C18 17.6569 16.6569 19 15 19H4C2.34312 19 1 17.6569 1 16V8C1 6.34312 2.34312 5 4 5H15Z");
}

</style>
