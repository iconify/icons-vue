<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp44myboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-referee" /></template>
<style>
.zp44myboj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.079 2.273L12 5.82l2.921-3.547q.047-.057.104-.104t.123-.081q.065-.035.136-.056q.07-.021.144-.029q.073-.007.147.001q.073.007.144.029q.071.021.136.056t.122.082q.115.095.185.227q.07.131.085.28q.014.148-.03.291q-.043.143-.138.258l-2.49 3.023H19.5q2.75 0 2.75 2.75v9.5q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75V9q0-1.139.805-1.945q.806-.805 1.945-.805h5.911l-2.49-3.023q-.095-.115-.138-.258t-.03-.291q.015-.149.085-.28t.185-.227q.057-.047.122-.082t.136-.056t.144-.029t.147-.001q.074.008.144.029q.071.021.136.056t.123.081q.057.047.104.104M7.893 19.75h8.214q-.637-1.5-4.107-1.5t-4.107 1.5m9.793 0H19.5q1.25 0 1.25-1.25V9q0-1.25-1.25-1.25h-15q-.518 0-.884.366T3.25 9v9.5q0 1.25 1.25 1.25h1.814q.543-3 5.686-3t5.686 3M12 9q-3.25 0-3.25 3.25T12 15.5t3.25-3.25T12 9");
}

</style>
