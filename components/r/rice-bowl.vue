<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx_m9wc7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rice-bowl" /></template>
<style>
.cx_m9wc7y {
  fill: currentColor;
  d: path("M9 21v-1.423q-2.51-.993-4.255-2.971T3 12q0-1.868.709-3.51T5.63 5.633t2.857-1.924T11.997 3t3.51.709t2.859 1.924t1.925 2.857T21 12q0 2.627-1.745 4.606T15 19.577V21zm.5-9h5V4.404q-.622-.202-1.243-.303Q12.634 4 12.004 4t-1.26.101t-1.245.303zM4 12h4.5V4.806Q6.433 5.823 5.216 7.76Q4 9.696 4 12m11.5 0H20q0-2.304-1.216-4.24q-1.217-1.937-3.284-2.954z");
}

</style>
