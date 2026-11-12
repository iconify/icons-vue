<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1zd0w05n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-portrait-long-outline" /></template>
<style>
.d1zd0w05n {
  fill: currentColor;
  d: path("M13 20v-2h4V5H7V3h10q.825 0 1.413.588T19 5v13q0 .825-.587 1.413T17 20zM4 10V7h1V5q0-.85.563-1.425T7 3q.225 0 .475.05t.575.163t.762.287t1.038.45q.525.225 1.112.538t1.813.887q.55.275.888.775T14 7.225V20q0 1.125-.913 1.725t-1.862.1q-1.35-.65-2.675-1.075t-2.05-.625q-.675-.15-1.088-.7T5 18.175V17H4v-3h1v-4zm8-2.8q-1.1-.575-2.45-1.213T7 5v13.175q1.175.275 2.538.788T12 20zM7 5v13.175zm10 0v13z");
}

</style>
