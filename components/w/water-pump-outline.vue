<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re5drtc9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-pump-outline" /></template>
<style>
.re5drtc9z {
  fill: currentColor;
  d: path("M3.5 17h5.254q-.713-.444-1.288-1.079q-.574-.634-.925-1.421H3.5zm12.038-1.463Q17 14.076 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463M17.46 9.5h3.04V7h-5.254q.714.444 1.288 1.079q.574.634.926 1.421M2.5 18.77v-6.04h1v.77h2.71q-.108-.365-.159-.737T6 12q0-2.502 1.749-4.251T12 6h8.5v-.77h1v6.04h-1v-.77h-2.71q.108.366.159.738T18 12q0 2.502-1.749 4.251T12 18H3.5v.77zm1-1.77v-2.5zm17-7.5V7zm-9.566 4.278q-.434-.434-.434-1.066q0-.402.18-.82t.643-1.123l.658-.98l.677.98q.502.743.672 1.142t.17.8q0 .633-.434 1.067q-.433.434-1.066.434t-1.066-.434");
}

</style>
