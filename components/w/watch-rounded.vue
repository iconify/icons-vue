<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubwbwmbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-rounded" /></template>
<style>
.ubwbwmbrx {
  fill: currentColor;
  d: path("M10.73 21q-.341 0-.61-.205t-.372-.547l-.632-2.214q-.131-.423-.396-.81q-.264-.388-.707-.765q-.965-.809-1.489-1.965T6 12q0-1.313.524-2.47t1.49-1.99q.442-.402.706-.786q.264-.385.395-.788l.633-2.214q.104-.342.372-.547T10.73 3h2.54q.342 0 .61.205t.372.547l.633 2.214q.13.423.395.81q.264.388.707.765q.965.809 1.489 1.965T18 12q0 1.314-.524 2.47t-1.49 1.99q-.442.402-.706.786q-.264.385-.395.789l-.633 2.213q-.104.343-.372.547t-.61.205zm4.808-5.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463");
}

</style>
