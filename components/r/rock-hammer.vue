<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7pojdbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rock-hammer" /></template>
<style>
.p7pojdbyk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 3.25h-3Q2.75 3.25 2.75 5v4q0 1.75 1.75 1.75h3q1.479 0 1.708-1.25h1.542V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9.5H14q.043 0 .086-.005l6.5-.75q.099-.011.191-.048q.093-.037.173-.097q.079-.059.141-.138q.061-.078.1-.17q.058-.137.059-.286q.001-.15-.055-.288t-.161-.244q-.104-.107-.242-.165l-6.5-2.75Q14.152 4.5 14 4.5H9.208Q8.979 3.25 7.5 3.25");
}

</style>
