<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-xdmc_mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-tap-outline-sharp" /></template>
<style>
.u-xdmc_mu {
  fill: currentColor;
  d: path("M11.558 3H20zM3 8.154Q3 6.019 4.51 4.51T8.154 3v1q-1.727 0-2.94 1.214T4 8.153zM3 21V10.558h10.442V21h-1v-9.442H4V21zM6.692 8.154q0-.614.424-1.038q.425-.424 1.038-.424v1.462zm2.04 6.251q.21-.21.21-.52t-.21-.52t-.52-.211t-.52.21t-.211.52t.21.52t.52.212t.52-.21m1.827-6.252V3h1v5.154zM15.846 21v-1q1.727 0 2.94-1.213T20 15.847h1q0 2.134-1.51 3.644Q17.98 21 15.847 21m0-3.692v-1.462h1.462q0 .613-.424 1.038q-.424.424-1.038.424m0-3.866v-1H20V3h1v10.442zM12.442 21H4z");
}

</style>
