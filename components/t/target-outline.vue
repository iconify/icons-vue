<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb5u5kb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:target-outline" /></template>
<style>
.yb5u5kb-q {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708m9.182-2.617Q20 15.35 20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325m-9.214-2.132Q7 14.086 7 12.005T8.457 8.46T11.995 7t3.544 1.457T17 11.995t-1.457 3.544T12.005 17T8.46 15.543m6.364-.718Q16 13.65 16 12t-1.175-2.825T12 8T9.175 9.175T8 12t1.175 2.825T12 16t2.825-1.175m-3.526-2.124Q11 12.402 11 12t.299-.701T12 11t.701.299T13 12t-.299.701T12 13t-.701-.299");
}

</style>
