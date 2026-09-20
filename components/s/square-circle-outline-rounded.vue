<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_lajo2ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:square-circle-outline-rounded" /></template>
<style>
.m_lajo2ul {
  fill: currentColor;
  d: path("M9 15.808h6q.343 0 .576-.233t.232-.575V9q0-.343-.233-.575T15 8.192H9q-.343 0-.575.232T8.192 9v6q0 .343.232.576t.576.232m.192-1V9.192h5.616v5.616zm-.698 5.491q-1.642-.701-2.867-1.926t-1.926-2.866T3 12.003t.701-3.508t1.926-2.857T8.493 3.71T11.998 3t3.509.709t2.859 1.922t1.925 2.857t.709 3.509t-.71 3.509t-1.926 2.867t-2.856 1.926t-3.506.701t-3.508-.701M11.991 20q3.334 0 5.672-2.328T20 12.009t-2.337-5.671T12 4Q8.656 4 6.328 6.338T4 12q0 3.344 2.328 5.672T11.991 20M12 12");
}

</style>
