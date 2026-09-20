<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anyyiqr2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unsubscribe" /></template>
<style>
.anyyiqr2h {
  fill: currentColor;
  d: path("m12 12.116l8-5.212L19.692 6L12 11L4.308 6L4 6.904zm4.165 8.72Q15 19.67 15 18t1.165-2.835T19 14t2.836 1.165T23 18t-1.164 2.836T19 22t-2.835-1.164m.489-2.451h4.692v-.77h-4.692zM4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v5.738q-.488-.177-.988-.265T19 12q-2.502 0-4.251 1.749T13 18q0 .25.017.5t.09.5z");
}

</style>
