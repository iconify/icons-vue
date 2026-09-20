<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhdt4b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-sharp" /></template>
<style>
.zyhdt4b7h {
  fill: currentColor;
  d: path("M10.02 17.885q-2.02 0-3.453-1.433T5.134 13q0-.346.054-.691q.054-.346.123-.563q-.105.05-.223.056t-.213.006q-.81 0-1.352-.547t-.542-1.338t.524-1.338t1.324-.547q.69 0 1.209.405t.639 1.015q.633-.635 1.532-.989t1.81-.354h11v2h-6.115V13q0 2.035-1.425 3.46q-1.424 1.425-3.46 1.425m-4.441-7.25q.288-.287.288-.712t-.288-.712t-.712-.288t-.713.288t-.288.712t.288.713t.713.287t.712-.288m5.585 3.505q.472-.476.472-1.143t-.476-1.14t-1.143-.472t-1.14.475t-.472 1.144t.475 1.14t1.144.472t1.14-.476");
}

</style>
