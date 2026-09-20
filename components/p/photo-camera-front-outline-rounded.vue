<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6d-wjb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-camera-front-outline-rounded" /></template>
<style>
.t6d-wjb1o {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19V7q0-.825.588-1.412T4 5h3.15L8.4 3.65q.275-.3.663-.475T9.875 3h4.25q.425 0 .813.175t.662.475L16.85 5H20q.825 0 1.413.588T22 7v12q0 .825-.587 1.413T20 21zm0-2h16V7h-4.05l-1.825-2h-4.25L8.05 7H4zm4-2h8v-.55q0-1.125-1.1-1.787T12 14t-2.9.663T8 16.45zm5.413-4.587Q14 11.825 14 11t-.587-1.412T12 9t-1.412.588T10 11t.588 1.413T12 13t1.413-.587");
}

</style>
