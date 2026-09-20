<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yle_dcbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-very-dissatisfied-outline" /></template>
<style>
.yle_dcbtb {
  fill: currentColor;
  d: path("M9.365 14.29q-1.206.789-1.811 2.095h8.892q-.606-1.306-1.81-2.095T12 13.5t-2.636.79m-1.641-2.713l1.1-1.05l1.05 1.05l.627-.627L9.45 9.9l1.05-1.1l-.627-.627l-1.05 1.05l-1.1-1.05l-.627.627l1.05 1.1l-1.05 1.05zm6.404 0l1.05-1.05l1.1 1.05l.627-.627l-1.05-1.05l1.05-1.1l-.627-.627l-1.1 1.05l-1.05-1.05l-.627.627l1.05 1.1l-1.05 1.05zm-5.634 8.715q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708m9.182-2.617Q20 15.35 20 12t-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325");
}

</style>
