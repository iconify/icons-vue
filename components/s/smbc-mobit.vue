<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bru9dbdbf"/><path class="qg8ykubra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smbc-mobit" /></template>
<style>
.bru9dbdbf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 7.5a4 4 0 0 0-3.639 2.338l-8 17.5C4.651 29.988 6.588 33 9.5 33h21a4 4 0 0 0 3.639-2.338l8-17.5c1.21-2.649-.727-5.661-3.639-5.662z");
}

.qg8ykubra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.26 32.803l23 7.5a4 4 0 0 0 4.935-2.273l6-14.5a4 4 0 0 0-2.37-5.304m-20.305.119c.655-1.433 2.333-2.594 3.749-2.594s2.031 1.161 1.376 2.594l-1.957 4.28m-1.982-6.875l-3.143 6.875m7.082-4.28c.655-1.433 2.333-2.594 3.749-2.594s2.031 1.161 1.376 2.594l-1.957 4.28");
}

</style>
