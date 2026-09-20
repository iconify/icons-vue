<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyodg3b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:seat-read-sharp" /></template>
<style>
.kyodg3b9l {
  fill: currentColor;
  d: path("M7.23 7.577q-.69 0-1.19-.501t-.501-1.191t.5-1.192t1.192-.5t1.191.5t.501 1.191q0 .691-.501 1.192q-.5.501-1.191.501m10.808 14.807L15.484 18H8.267q-.552 0-.946-.332t-.504-.845l-1.172-5.644q-.205-.95.413-1.69q.618-.739 1.587-.739q.504 0 .941.209q.438.208.774.587l2.743 3.018l2.692-2.058l-.794-.414q-.142-.08-.185-.236t.018-.298l.904-1.994q.08-.162.239-.218t.32.025l1.062.529q.142.08.188.24q.046.158-.015.3l-.81 1.802l.412.544l-4.05 3.255l-1.79-1.395l.773 3.354h3.6q.39 0 .724.198q.335.198.552.571l2.962 5.116zM12.96 20H7.01q-.69 0-1.243-.443q-.552-.443-.69-1.134L3 8h1.012l2.084 10.385q.038.23.27.423q.23.192.461.192h6.134z");
}

</style>
