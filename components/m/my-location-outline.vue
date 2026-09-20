<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsx_aefqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:my-location-outline" /></template>
<style>
.bsx_aefqf {
  fill: currentColor;
  d: path("M11.5 21.45v-1.461q-3.125-.293-5.16-2.328q-2.036-2.036-2.328-5.161H2.55v-1h1.462q.292-3.125 2.328-5.16t5.16-2.328V2.55h1v1.462q3.125.292 5.16 2.328t2.329 5.16h1.461v1h-1.461q-.293 3.125-2.328 5.16q-2.036 2.036-5.161 2.329v1.461zm5.45-4.5Q19 14.9 19 12t-2.05-4.95T12 5T7.05 7.05T5 12t2.05 4.95T12 19t4.95-2.05m-7.073-2.827Q9 13.246 9 12t.877-2.123T12 9t2.123.877T15 12t-.877 2.123T12 15t-2.123-.877m3.536-.71Q14 12.825 14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14t1.413-.587M12 12");
}

</style>
