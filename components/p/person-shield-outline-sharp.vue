<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmj1kebwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-shield-outline-sharp" /></template>
<style>
.wmj1kebwu {
  fill: currentColor;
  d: path("M12.352 18.616H5v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34v1q-1.335 0-2.646.319t-2.546.916q-.38.202-.593.494Q6 16.637 6 16.97v.647h6.087q.04.262.107.512q.066.25.158.488M17.692 21q-1.517-.373-2.412-1.679q-.895-1.305-.895-2.906v-2.13l3.307-1.67L21 14.288v2.131q0 1.589-.895 2.898q-.896 1.31-2.413 1.683m0-1.004q1.104-.373 1.716-1.384t.611-2.196v-1.532l-2.327-1.153l-2.327 1.153v1.531q0 1.185.612 2.196t1.715 1.385m-7.815-9.488Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711Q14 9.21 14 8.385t-.588-1.413T12 6.385t-1.413.587T10 8.385t.587 1.412t1.413.588t1.412-.588m4.28 7.067");
}

</style>
