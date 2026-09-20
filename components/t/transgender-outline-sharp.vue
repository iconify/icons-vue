<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waevbb0wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transgender-outline-sharp" /></template>
<style>
.waevbb0wu {
  fill: currentColor;
  d: path("M14.83 14.33Q16 13.163 16 11.5t-1.17-2.83T12 7.5T9.17 8.67T8 11.5t1.17 2.83T12 15.5t2.83-1.17M11.5 22.5v-2h-2v-1h2v-3.023q-1.911-.235-3.206-1.644Q7 13.423 7 11.5q0-.863.286-1.673q.285-.81.818-1.504L6.608 6.827l-1.4 1.4l-.689-.688l1.4-1.406L3 3.213V6.5H2v-5h5v1H3.714l2.919 2.92l1.405-1.4l.689.688l-1.4 1.405L8.842 7.63q.675-.538 1.485-.834T12 6.5t1.673.295t1.485.834L20.287 2.5H17v-1h5v5h-1V3.214l-5.129 5.122q.533.681.831 1.488T17 11.5q0 1.923-1.294 3.333T12.5 16.477V19.5h2v1h-2v2z");
}

</style>
