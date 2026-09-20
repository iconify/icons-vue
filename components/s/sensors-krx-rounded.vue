<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xudkembqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensors-krx-rounded" /></template>
<style>
.xudkembqh {
  fill: currentColor;
  d: path("M4.26 14.103q.261 1.018.801 1.895q.123.202.1.416t-.213.342q-.177.135-.382.06q-.205-.074-.314-.256q-.614-1.037-.933-2.17T3 12t.32-2.395q.319-1.14.932-2.17q.11-.183.314-.254t.382.063q.19.129.214.342t-.1.416q-.54.877-.801 1.895T4 12t.26 2.103m3.769 1.868Q6.385 14.327 6.385 12t1.644-3.971T12 6.385t3.971 1.644T17.616 12t-1.645 3.971T12 17.616T8.029 15.97m11.7-6.074q-.27-1.018-.81-1.895q-.123-.202-.093-.415t.22-.343q.177-.134.385-.063t.317.254q.614 1.03.933 2.17T21 12t-.32 2.39q-.318 1.133-.932 2.17q-.11.182-.317.256t-.385-.06q-.19-.129-.22-.343t.093-.415q.54-.877.81-1.895Q20 13.085 20 12t-.27-2.103");
}

</style>
