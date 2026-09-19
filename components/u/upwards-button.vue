<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ss891vbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:upwards-button" /></template>
<style>
.ss891vbhh {
  fill: currentColor;
  d: path("M53.213 10.788c-11.715-11.717-30.711-11.717-42.426 0c-11.716 11.715-11.716 30.71 0 42.426c11.715 11.715 30.711 11.715 42.426 0c11.717-11.716 11.717-30.711 0-42.426M12 38l20-20l20 20z");
}

</style>
