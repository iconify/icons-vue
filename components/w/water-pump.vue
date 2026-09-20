<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvd2uimsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-pump" /></template>
<style>
.dvd2uimsh {
  fill: currentColor;
  d: path("m11.98 9.789l-.657.98q-.521.8-.672 1.16q-.151.362-.151.783q0 .632.434 1.066q.433.434 1.066.434t1.066-.434t.434-1.066q0-.402-.16-.792q-.161-.39-.682-1.15zm-4.107 6.338q-1.7-1.7-1.7-4.127t1.7-4.127T12 6.173t4.127 1.7t1.7 4.127t-1.7 4.127t-4.127 1.7t-4.127-1.7M20.5 11.269V10.5h-1.979q-.333-1.5-1.255-2.665Q16.344 6.672 15.017 6H20.5v-.77h1v6.04zm-18 7.5v-6.038h1v.769h1.979q.332 1.5 1.255 2.665q.922 1.164 2.249 1.835H3.5v.77z");
}

</style>
