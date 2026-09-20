<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxawh12vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speech-to-text-2-outline" /></template>
<style>
.jxawh12vs {
  fill: currentColor;
  d: path("M19 4v16zM8.616 21q-.672 0-1.144-.472T7 19.385V17.73h1v1.654q0 .269.173.442t.443.173h9.769q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T18.385 4H11.5V3h6.885q.67 0 1.143.472q.472.472.472 1.144v14.769q0 .67-.472 1.143q-.472.472-1.143.472zM7.5 9.885q-.639 0-1.07-.431T6 8.384V4q0-.639.43-1.07T7.5 2.5q.614 0 1.057.43T9 4v4.385q0 .638-.443 1.069t-1.057.43M7 15.5v-2.523q-1.833-.171-3.109-1.424Q2.616 10.3 2.616 8.5h1q0 1.52 1.163 2.51T7.5 12t2.721-.99t1.163-2.51h1q0 1.8-1.275 3.053Q9.833 12.806 8 12.977V15.5zm3.5 2.23h6v-1h-6zm0-3h4v-1h-4z");
}

</style>
