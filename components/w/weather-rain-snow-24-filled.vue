<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz_6jobow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-rain-snow-24-filled" /></template>
<style>
.lz_6jobow {
  fill: currentColor;
  d: path("M14.534 17.553a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M12 4.001c3.169 0 4.966 2.097 5.227 4.63h.08A3.687 3.687 0 0 1 21 12.314a3.687 3.687 0 0 1-3.692 3.682L16 15.997a.75.75 0 0 1-1.433 0l-5.58-.001l-1.582 2.629a.75.75 0 0 1-1.344-.659l.045-.091l1.15-1.879h-.563A3.687 3.687 0 0 1 3 12.314A3.687 3.687 0 0 1 6.693 8.63h.08C7.035 6.08 8.831 4 12 4m-.422 12.704a.75.75 0 0 1 .32.933l-.046.091l-.556.896a.75.75 0 0 1-1.345-.658l.045-.092l.557-.896a.75.75 0 0 1 1.025-.274m5.455.098a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
