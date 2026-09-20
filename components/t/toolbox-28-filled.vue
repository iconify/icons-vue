<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e6q-mbc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toolbox-28-filled" /></template>
<style>
.e6q-mbc1m {
  fill: currentColor;
  d: path("M8.002 6.247v1.748H4.25A2.25 2.25 0 0 0 2 10.245V14h5.506v-1.25a.75.75 0 0 1 1.5 0V14h10v-1.25a.75.75 0 0 1 1.5 0V14h5.497v-3.755a2.25 2.25 0 0 0-2.25-2.25h-3.75V6.247a2.25 2.25 0 0 0-2.25-2.25h-7.5a2.25 2.25 0 0 0-2.25 2.25m2.25-.75h7.501a.75.75 0 0 1 .75.75v1.748h-9V6.247a.75.75 0 0 1 .75-.75M26.003 15.5h-5.497v1.25a.75.75 0 0 1-1.5 0V15.5h-10v1.25a.75.75 0 0 1-1.5 0V15.5H2v6.245a2.25 2.25 0 0 0 2.25 2.25h19.504a2.25 2.25 0 0 0 2.25-2.25z");
}

</style>
