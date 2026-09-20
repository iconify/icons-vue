<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfg6jtbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:surround-sound" /></template>
<style>
.yfg6jtbig {
  fill: currentColor;
  d: path("M13.635 13.635q.673-.673.673-1.635t-.673-1.634q-.673-.674-1.635-.674t-1.634.674q-.674.673-.674 1.634t.674 1.635t1.634.673t1.635-.674m3.277 2.585q.769-.885 1.16-1.967t.39-2.252t-.39-2.252q-.391-1.083-1.16-1.967l-.708.707q.61.745.933 1.647q.324.903.324 1.865t-.323 1.864t-.934 1.647zm-9.823 0l.707-.708q-.61-.744-.934-1.647T6.539 12t.324-1.865q.324-.902.934-1.647l-.708-.707q-.769.884-1.16 1.967T5.539 12t.39 2.252q.391 1.082 1.16 1.967M4.617 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
