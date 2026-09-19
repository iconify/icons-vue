<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k2sp4_m7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:right-arrow-curving-left" /></template>
<style>
.k2sp4_m7y {
  fill: currentColor;
  d: path("M53.213 10.786c-11.715-11.715-30.711-11.715-42.426 0c-11.716 11.717-11.716 30.711 0 42.428c11.715 11.715 30.711 11.715 42.426 0c11.716-11.717 11.716-30.711 0-42.428M33.297 50.835h-7.082v5.164L17 46.263l9.215-9.736v6.131h7.082c5.314 0 9.806-5.139 9.806-11.223c0-6.209-4.882-11.26-10.881-11.26h-8.969v-8.176h8.969C42.576 11.999 51 20.718 51 31.435c0 10.515-8.107 19.4-17.703 19.4");
}

</style>
