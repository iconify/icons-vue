<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfw5plbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-horizontal-sharp-fill" /></template>
<style>
.rfw5plbqn {
  fill: currentColor;
  d: path("M17 15C18.832 15 20.398 16.32 20.872 18H23V20H20.872C20.398 21.68 18.832 23 17 23H15C13.362 23 11.954 22.01 11.336 20.6L11.223 20.32L11.127 20H1V18H11.128C11.602 16.32 13.168 15 15 15H17ZM22 1C22.552 1 23 1.45 23 2V12C23 12.55 22.552 13 22 13H2C1.448 13 1 12.55 1 12V2C1 1.45 1.448 1 2 1H22Z");
}

</style>
