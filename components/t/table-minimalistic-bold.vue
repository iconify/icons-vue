<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3lzwvbgs"/><path class="lcfo8_bek"/><path class="tiy7a-vsh"/><path class="n-k1pzbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-minimalistic-bold" /></template>
<style>
.lcfo8_bek {
  fill: currentColor;
  d: path("M8.25 9.41675V21.9724C6.22916 21.9063 5.01539 21.6721 4.17188 20.8289C3.0003 19.6573 3 17.771 3 13.9998V9.99976C3 9.8002 3.0008 9.60592 3.00098 9.41675H8.25Z");
}

.n-k1pzbhc {
  fill: currentColor;
  d: path("M8.25 7.91675H3.0127C3.05153 5.48888 3.2394 4.10411 4.17188 3.17163C5.01541 2.32818 6.22892 2.09225 8.25 2.02612V7.91675Z");
}

.n3lzwvbgs {
  fill: currentColor;
  d: path("M21 9.99976V13.9998C21 17.771 20.9997 19.6573 19.8281 20.8289C18.6565 22.0001 16.7708 21.9998 13 21.9998H11C10.5581 21.9998 10.142 21.9997 9.75 21.9978V9.41675H20.999C20.9992 9.60592 21 9.8002 21 9.99976Z");
}

.tiy7a-vsh {
  fill: currentColor;
  d: path("M13 1.99976C16.7711 1.99976 18.6565 2.00017 19.8281 3.17163C20.7606 4.10411 20.9485 5.48888 20.9873 7.91675H9.75V2.00171C10.142 1.99982 10.5581 1.99976 11 1.99976H13Z");
}

</style>
