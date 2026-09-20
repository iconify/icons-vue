<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjs76r_qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scatter-plot" /></template>
<style>
.tjs76r_qy {
  fill: currentColor;
  d: path("M14.646 18.892q-.877-.876-.877-2.123t.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.123q-.876.877-2.123.877t-2.123-.877m-9.538-3q-.877-.876-.877-2.123t.877-2.123q.877-.877 2.123-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877m3.769-7.384Q8 7.63 8 6.385t.877-2.123T11 3.385t2.123.877T14 6.385t-.877 2.123T11 9.385t-2.123-.877");
}

</style>
