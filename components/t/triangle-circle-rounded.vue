<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckcx3bccv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:triangle-circle-rounded" /></template>
<style>
.ckcx3bccv {
  fill: currentColor;
  d: path("M8.494 20.299q-1.642-.701-2.867-1.926t-1.926-2.866T3 12.003t.701-3.508t1.926-2.857T8.493 3.71T11.998 3t3.509.709t2.859 1.922t1.925 2.857t.709 3.509t-.71 3.509t-1.926 2.867t-2.856 1.926t-3.506.701t-3.508-.701m.031-5.433h6.93q.463 0 .704-.407t-.003-.815l-3.46-5.757q-.246-.385-.698-.385t-.694.385l-3.478 5.739q-.245.407-.004.823q.241.417.703.417m.346-1L12 8.689l3.104 5.177z");
}

</style>
