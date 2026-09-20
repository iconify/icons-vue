<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhe9-lvqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-contact-calendar-sharp" /></template>
<style>
.qhe9-lvqh {
  fill: currentColor;
  d: path("M5 19.12q1.35-1.326 3.138-2.088T12 16.269t3.863.763T19 19.119V6H5zm4.871-6.491Q9 11.758 9 10.5t.871-2.129T12 7.5t2.129.871T15 10.5t-.871 2.129T12 13.5t-2.129-.871M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16z");
}

</style>
