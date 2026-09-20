<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a57lx3r6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toggle-off" /></template>
<style>
.a57lx3r6o {
  fill: currentColor;
  d: path("M7 17q-2.083 0-3.542-1.457T2 12.005T3.458 8.46Q4.917 7 7 7h10q2.083 0 3.542 1.457T22 11.995t-1.458 3.544Q19.083 17 17 17zm1.77-3.228q.73-.729.73-1.77t-.728-1.771t-1.77-.731t-1.771.729t-.731 1.769t.729 1.771t1.769.731t1.771-.728");
}

</style>
