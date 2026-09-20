<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsmt1ebas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:y-circle-outline-rounded" /></template>
<style>
.hsmt1ebas {
  fill: currentColor;
  d: path("M11.546 13.612v3.467q0 .196.132.328q.132.131.328.131t.328-.131t.132-.328v-3.512l2.759-5.155q.104-.197.042-.359t-.22-.236q-.16-.073-.326-.045q-.165.028-.269.224L12 12.6L9.566 7.996Q9.46 7.8 9.29 7.77t-.33.048q-.16.08-.225.254q-.064.175.046.371zm-3.052 6.687q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701M12 20q3.325 0 5.663-2.328T20 12q0-3.325-2.337-5.663T12 4Q8.656 4 6.328 6.338T4 12q0 3.344 2.328 5.672T12 20m0-8");
}

</style>
