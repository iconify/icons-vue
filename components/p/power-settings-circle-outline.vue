<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caw322b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-settings-circle-outline" /></template>
<style>
.caw322b_e {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708m9.182-2.617Q20 15.35 20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325m-2.136-2.136Q17 14.077 17 12.005q0-1.057-.388-1.958q-.389-.9-1.073-1.586l-.714.714q.55.55.863 1.275T16 12q0 1.65-1.175 2.825T12 16t-2.825-1.175T8 12q0-.825.313-1.55t.862-1.275l-.713-.713q-.685.684-1.073 1.585Q7 10.95 7 12.005q0 2.072 1.457 3.534T11.995 17t3.544-1.461M11.5 12h1V7h-1zm.5 0");
}

</style>
