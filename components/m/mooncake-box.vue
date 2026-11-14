<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oncki6bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mooncake-box" /></template>
<style>
.oncki6bjs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.43q-1.745-.705-3.535.027q-1.792.734-2.543 2.465q-1.731.751-2.465 2.543q-.732 1.79-.027 3.535q-.705 1.745.027 3.535q.734 1.792 2.465 2.543q.751 1.731 2.543 2.465q1.79.732 3.535.027q1.745.705 3.535-.027q1.792-.734 2.543-2.465q1.731-.751 2.465-2.543q.732-1.79.027-3.535q.705-1.745-.027-3.535q-.734-1.792-2.465-2.543q-.751-1.731-2.543-2.465q-1.79-.732-3.535-.027M6.25 12q0-2.875 2.543-3.207Q9.125 6.25 12 6.25t3.207 2.543Q17.75 9.125 17.75 12t-2.543 3.207Q14.875 17.75 12 17.75t-3.207-2.543Q6.25 14.875 6.25 12");
}

</style>
