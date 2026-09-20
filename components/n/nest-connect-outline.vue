<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz5fr0bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-connect-outline" /></template>
<style>
.bz5fr0bqh {
  fill: currentColor;
  d: path("M15.182 17.182Q16.5 15.864 16.5 14v-4q0-1.864-1.318-3.182T12 5.5T8.818 6.818T7.5 10v4q0 1.864 1.318 3.182T12 18.5t3.182-1.318m-5.663-.701Q8.5 15.46 8.5 14v-4q0-1.461 1.02-2.48T12 6.5t2.48 1.02T15.5 10v4q0 1.462-1.02 2.48T12 17.5t-2.48-1.02m3.02-6.94q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M5.616 22q-.672 0-1.144-.472T4 20.385V3.615q0-.67.472-1.143Q4.944 2 5.616 2h12.769q.67 0 1.143.472q.472.472.472 1.144v16.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h12.769q.269 0 .442-.173t.173-.442V3.615q0-.269-.173-.442T18.385 3H5.615q-.269 0-.442.173T5 3.616v16.769q0 .269.173.442t.443.173M5 21V3z");
}

</style>
