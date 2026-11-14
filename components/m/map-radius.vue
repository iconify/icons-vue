<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcugk8bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-radius" /></template>
<style>
.tcugk8bgx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.789 4.859l4.25-1.771q.961-.401 1.922 0l4.655 1.94q.384.16.769 0l2.904-1.21q1.234-.515 2.348.227t1.113 2.08v10.708q.001 1.667-1.539 2.308l-4.25 1.771q-.961.401-1.922 0l-4.655-1.94q-.384-.16-.769 0l-2.904 1.21q-1.234.515-2.348-.227t-1.113-2.08V7.167Q2.249 5.5 3.789 4.859m4.675 3.855Q7 10.179 7 12.25t1.464 3.536T12 17.25t3.536-1.464Q17 14.321 17 12.25t-1.464-3.536T12 7.25T8.464 8.714");
}

</style>
