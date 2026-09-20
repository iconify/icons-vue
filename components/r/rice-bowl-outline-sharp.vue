<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_xbgnb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rice-bowl-outline-sharp" /></template>
<style>
.e_xbgnb6d {
  fill: currentColor;
  d: path("M9 21v-1.423q-2.51-.993-4.255-2.971T3 12q0-1.864.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12q0 2.627-1.745 4.606T15 19.577V21zm.5-9h5V4.404q-.615-.202-1.24-.303T12 4t-1.26.101t-1.24.303zM4 12h4.5V4.806Q6.433 5.823 5.216 7.76Q4 9.696 4 12m11.5 0H20q0-2.304-1.216-4.24q-1.217-1.937-3.284-2.954zM10 20h4v-1.1q2.108-.84 3.787-2.287T19.869 13H4.131q.403 2.166 2.082 3.613Q7.893 18.06 10 18.9zm0 0h4z");
}

</style>
