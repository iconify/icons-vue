<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzqyvvbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:private-connectivity-sharp" /></template>
<style>
.mzqyvvbnv {
  fill: currentColor;
  d: path("M7.916 16.413Q6.194 14.825 6.017 12.5H2.384v-1h3.633q.177-2.325 1.9-3.912Q9.638 6 12 6t4.084 1.588t1.899 3.912h3.632v1h-3.632q-.177 2.325-1.9 3.913Q14.363 18 12 18t-4.084-1.588m1.2-1.143h5.768V10.5h-1v-.784q0-.818-.536-1.401Q12.811 7.73 12 7.73q-.787 0-1.336.549t-.548 1.336v.884h-1zM12 13.596q-.287 0-.499-.212t-.213-.5t.213-.498t.499-.213t.499.213t.213.499t-.213.499t-.499.212M10.885 10.5v-.885q0-.463.326-.789T12 8.5t.79.326t.326.79v.884z");
}

</style>
