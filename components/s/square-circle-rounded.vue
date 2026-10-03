<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb99us4si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:square-circle-rounded" /></template>
<style>
.mb99us4si {
  fill: currentColor;
  d: path("M8.494 20.299q-1.642-.701-2.867-1.926t-1.926-2.866T3 12.003t.701-3.508t1.926-2.857T8.493 3.71T11.998 3t3.509.709t2.859 1.922t1.925 2.857t.709 3.509t-.71 3.509t-1.926 2.867t-2.856 1.926t-3.506.701t-3.508-.701M9 15.808h6q.343 0 .576-.233t.232-.575V9q0-.343-.233-.575T15 8.192H9q-.343 0-.575.232T8.192 9v6q0 .343.232.576t.576.232m.192-1V9.192h5.616v5.616z");
}

</style>
