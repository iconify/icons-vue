<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvyp3oerc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-patient-outline-sharp" /></template>
<style>
.xvyp3oerc {
  fill: currentColor;
  d: path("M5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.673 0 1.346.081t1.346.243v1.005q-.673-.177-1.346-.253q-.673-.075-1.346-.075q-1.335 0-2.646.318t-2.546.916q-.38.202-.593.494Q6 16.637 6 16.97v.647h8.692v1zm1-1h8.692zm3.877-7.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711Q14 9.21 14 8.385t-.588-1.413T12 6.385t-1.413.587T10 8.385t.587 1.412t1.413.588t1.412-.588M18.5 22.116v-3.808h-1.423V13.5h4.115l-1.826 3.616h1.769z");
}

</style>
