<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juzxcbcgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sell-cloud-rounded" /></template>
<style>
.juzxcbcgm {
  fill: currentColor;
  d: path("M6.635 21h.6q.373 0 .56-.31q.186-.311.044-.66q-.131-.367-.177-.756q-.046-.39-.046-.774q0-1.579.913-2.834t2.412-1.749q.768-1.063 1.963-1.68t2.59-.616h.413q.212 0 .412.05q.373.056.65-.159t.275-.562V9.158q.006-.324-.115-.628q-.121-.305-.339-.547l-4.488-4.517q-.242-.243-.547-.354T11.127 3q-.298 0-.615.121q-.318.121-.535.344L5.46 7.983q-.237.236-.348.528T5 9.153v10.214q0 .701.466 1.168q.467.466 1.168.466m4.482-12.629q-.414 0-.711-.303t-.309-.716q.012-.414.309-.717q.297-.302.71-.302q.414 0 .708.302q.294.303.312.717q-.018.413-.312.716t-.707.303M12.5 21q-1.044 0-1.772-.728T10 18.5q0-1.008.72-1.726t1.765-.768q.361-.9 1.18-1.453q.818-.553 1.818-.553q1.194 0 2.127.682q.934.682 1.1 1.818h.25q.874 0 1.457.678T21 18.75q0 .914-.568 1.582T19 21z");
}

</style>
