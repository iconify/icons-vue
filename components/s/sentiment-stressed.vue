<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj2b14tpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-stressed" /></template>
<style>
.jj2b14tpp {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708M7.7 12.176L10.698 10L7.7 7.823l-.516.72L9.188 10l-2.002 1.458zm2.8 4.45l1.5-1.5l1.5 1.5l1.5-1.5l.975.975l.627-.627L15 13.873l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5l-1.602 1.602l.627.627l.975-.975zm5.8-4.45l.516-.72L14.814 10l2.001-1.458l-.515-.719L13.302 10z");
}

</style>
