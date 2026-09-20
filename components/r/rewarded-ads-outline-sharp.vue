<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpdr5zbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rewarded-ads-outline-sharp" /></template>
<style>
.gpdr5zbcf {
  fill: currentColor;
  d: path("M13.413 10.413Q14 9.825 14 9t-.587-1.412T12 7t-1.412.588T10 9t.588 1.413T12 11t1.413-.587M8.385 20v-1H11.5v-3.754q-1.283-.102-2.36-1.047q-1.079-.945-1.317-2.21q-1.586-.187-2.705-1.301T4 8V6h3.654V4h8.692v2H20v2q0 1.573-1.118 2.688t-2.705 1.3q-.238 1.266-1.316 2.211T12.5 15.246V19h3.116v1zm-.731-9.084V7H5v1q0 1.142.762 1.963t1.892.953m6.692 2.388q.962-.964.962-2.342V5H8.692v5.962q0 1.378.966 2.343q.966.964 2.346.964t2.342-.964m2-2.39q1.131-.132 1.892-.952T19 8V7h-2.654zM12 9.636");
}

</style>
