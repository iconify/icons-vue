<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ky0wqubjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wrench-screwdriver-28-regular" /></template>
<style>
.ky0wqubjx {
  fill: currentColor;
  d: path("M10.308 2.416a.75.75 0 0 1 .67-.11a6.499 6.499 0 0 1 .521 12.192V23.5a2.5 2.5 0 0 1-4.999 0v-9.001a6.499 6.499 0 0 1 .521-12.192A.75.75 0 0 1 8 3.02V7.5l.005.103A1 1 0 0 0 10 7.5V3.021a.75.75 0 0 1 .308-.605m11.793-.41a.75.75 0 0 1 .554.38l1.25 2.25a.75.75 0 0 1 .03.669L23 7.409V14h1.25a.75.75 0 0 1 .75.75v6.75a4.5 4.5 0 1 1-9 0v-6.75a.75.75 0 0 1 .75-.75H18V7.41l-.936-2.105a.75.75 0 0 1 .03-.67l1.25-2.25l.055-.084A.75.75 0 0 1 19 2h3zM11.5 7.5l-.013.256A2.5 2.5 0 0 1 6.5 7.5V4.17A5 5 0 0 0 4 8.5l.004.208a5 5 0 0 0 3.475 4.555a.75.75 0 0 1 .521.714V23.5a1 1 0 1 0 2 0v-9.522a.75.75 0 0 1 .521-.715a5 5 0 0 0 3.475-4.555L14 8.5a5 5 0 0 0-2.5-4.33zm6 14a3 3 0 1 0 6 0v-3h-6zm0-4.5h6v-1.5h-6zm1.087-11.964l.849 1.91c.042.095.064.2.064.304V14h2V7.25q0-.16.064-.305l.848-1.909L21.56 3.5h-2.12z");
}

</style>
