<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpl4y6b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tomb-of-the-mask" /></template>
<style>
.xpl4y6b4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.254 5.5H18.171v19.278h3.812v3.381h14.459v-3.381h3.812zM25.4 22.98h7.625m-20.256-6.151h5.402m-5.402-6.258h5.402m17.803 6.438v-3.524M25.4 17.009v-3.524m-7.229 17.841h18.27V42.5h-18.27zm9.135 4.624v6.55M12.434 24.778v-3.02m0 20.742v-5.812m5.737-11.91H7.746v11.91h4.688v-5.362h5.737z");
}

</style>
