<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9e5iubxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rss-feed" /></template>
<style>
.u9e5iubxs {
  fill: currentColor;
  d: path("M4.357 19.639Q4 19.277 4 18.769t.362-.869t.869-.361t.869.356t.362.874t-.357.874T5.23 20t-.874-.362M17.539 20q0-2.829-1.064-5.283t-2.902-4.29t-4.29-2.902Q6.827 6.461 4 6.461V5q3.127 0 5.846 1.18t4.756 3.218t3.217 4.752T19 20zM12 20q0-1.675-.625-3.113T9.65 14.35t-2.537-1.725T4 12v-1.461q1.973 0 3.691.737t3.005 2.029t2.026 3.003t.74 3.692z");
}

</style>
