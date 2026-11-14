<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfok2bc3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:points-gift" /></template>
<style>
.mfok2bc3c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.928 5.587l.898 1.909q.175.373.585.425l2.093.264q1.342.168 1.76 1.455t-.569 2.212l-1.538 1.444q-.1.094-.158.201q-1.083.1-1.717 1.081q-.277.428-.363.884q-1.234.704-1.395 2.482l-1.162-.639q-.362-.199-.723 0l-1.85 1.016q-1.184.652-2.278-.143q-1.095-.794-.841-2.123l.396-2.072q.078-.405-.223-.687l-1.538-1.444q-.987-.925-.569-2.212t1.761-1.455l2.092-.264q.41-.052.585-.425l.898-1.909Q9.647 4.363 11 4.363t1.928 1.224m6.528 9.171q-.81.115-1.456.867q-.646-.752-1.456-.867q-.815-.117-1.213.499q-.311.48-.109 1.075q-1.472.348-1.472 2.168v1.75q0 2.25 2.25 2.25h4q2.25 0 2.25-2.25V18.5q0-1.82-1.472-2.168q.202-.595-.109-1.075q-.398-.616-1.213-.499M17.25 17.75V21H16q-.75 0-.75-.75V18.5q0-.75.75-.75zm1.5 3.25v-3.25H20q.75 0 .75.75v1.75q0 .75-.75.75z");
}

</style>
