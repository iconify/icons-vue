<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqyzkccbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skydiver" /></template>
<style>
.kqyzkccbp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-9.75 0-9.75 8.25q0 .227.126.416q.043.065.099.119l.005.005l6.677 6.43Q9 17.407 9 18v2q0 2.25 2.25 2.25h1.5Q15 22.25 15 20v-2q0-.593-.157-1.03l6.677-6.43l.01-.01q.106-.105.163-.243T21.75 10q0-8.25-9.75-8.25M8.019 13.792l-3.745-3.606q1.302-.462 2.603.308zm3.231 1.958q-.523 0-.924.121l-1.915-5.532q1.586-.773 3.173.285q.092.062.199.094q.106.032.217.032t.217-.032t.199-.094q1.587-1.058 3.173-.285l-1.915 5.532q-.401-.121-.924-.121zm8.476-5.564l-3.745 3.606l1.142-3.298q1.301-.77 2.603-.308");
}

</style>
