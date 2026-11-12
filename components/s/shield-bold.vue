<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r62347llr"/><path class="s9_132ctu"/><path class="qdt5y7bmn"/><path class="v7zy9tb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-bold" /></template>
<style>
.qdt5y7bmn {
  fill: currentColor;
  d: path("M12.75 21.9596V9.04052L21 11.7905V11.9913C21 17.6294 16.761 20.3654 14.1014 21.5272C13.5907 21.7503 13.2608 21.8945 12.75 21.9596Z");
}

.r62347llr {
  fill: currentColor;
  d: path("M11.25 2.07336C10.6437 2.18646 9.93159 2.43023 8.83772 2.80466L8.26491 3.00074C5.25832 4.0299 3.75503 4.54449 3.37752 5.08236C3.00825 5.60848 3.00018 7.14969 3 10.2094L11.25 7.45938V2.07336Z");
}

.s9_132ctu {
  fill: currentColor;
  d: path("M11.25 9.04052L3 11.7905V11.9913C3 17.6294 7.23896 20.3654 9.89856 21.5272C10.4093 21.7503 10.7392 21.8944 11.25 21.9596V9.04052Z");
}

.v7zy9tb3t {
  fill: currentColor;
  d: path("M12.75 7.45938V2.07336C13.3563 2.18646 14.0684 2.43023 15.1623 2.80466L15.7351 3.00074C18.7417 4.0299 20.245 4.54449 20.6225 5.08236C20.9918 5.60848 20.9998 7.14969 21 10.2094L12.75 7.45938Z");
}

</style>
