<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7nn0vduk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-cart-outline-sharp" /></template>
<style>
.k7nn0vduk {
  fill: currentColor;
  d: path("M6.241 20.682q-.433-.434-.433-1.066t.433-1.067q.434-.433 1.067-.433t1.066.433t.434 1.067t-.434 1.066t-1.066.434t-1.067-.434m9.385 0q-.434-.434-.434-1.066t.434-1.067q.434-.433 1.066-.433t1.067.433q.433.434.433 1.067q0 .632-.433 1.066q-.434.434-1.067.434t-1.066-.434M5.881 5.5l2.669 5.616h7L18.627 5.5zm-.489-1h14.923l-4.167 7.616H8.1l-1.639 3h11.731v1H4.741l2.744-4.9L3.808 3.5H2v-1h2.442zm3.158 6.616h7z");
}

</style>
