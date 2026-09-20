<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dazc8gbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-settings-circle-rounded" /></template>
<style>
.dazc8gbrg {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708m7.046-4.75Q17 14.083 17 12q0-.847-.263-1.61t-.746-1.386q-.166-.231-.367-.255t-.378.08t-.228.296t.09.375q.426.514.66 1.157T16 12q0 1.65-1.175 2.825T12 16t-2.825-1.175T8 12q0-.721.233-1.37t.673-1.163q.134-.183.086-.362q-.048-.18-.219-.284t-.384-.079t-.38.262q-.488.617-.749 1.379Q7 11.144 7 12q0 2.083 1.457 3.542T11.995 17t3.544-1.458m-3.896-8.398q-.143.144-.143.356v4q0 .213.144.356t.357.144t.356-.144t.143-.356v-4q0-.213-.144-.356T11.999 7t-.356.144");
}

</style>
