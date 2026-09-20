<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h5nmsgbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pen-off-20-regular" /></template>
<style>
.h5nmsgbvb {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708L7.543 8.25l-3.998 3.997a2.44 2.44 0 0 0-.655 1.195l-.878 3.95a.5.5 0 0 0 .597.596l3.926-.873a2.5 2.5 0 0 0 1.234-.677l3.98-3.981l5.397 5.397a.5.5 0 0 0 .708-.708zm8.189 9.604l-3.981 3.98a1.5 1.5 0 0 1-.744.409l-3.16.703l.708-3.183a1.43 1.43 0 0 1 .387-.705L8.25 8.957zm5.377-5.378l-3.963 3.964l.707.707l2.586-2.586l.336.336a1 1 0 0 1 0 1.414l-.94.94a.5.5 0 1 0 .708.707l.939-.94a2 2 0 0 0 0-2.828l-.336-.336l.67-.67a2.975 2.975 0 0 0-4.207-4.208L8.957 6.837l.707.707l3.963-3.963a1.975 1.975 0 0 1 2.793 2.792");
}

</style>
