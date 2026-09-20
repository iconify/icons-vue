<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_edudb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-24-filled" /></template>
<style>
.k_edudb_m {
  fill: currentColor;
  d: path("M12 3c5.523 0 10 4.477 10 10c0 2.507-1.42 4.68-3.5 5.764V14a4 4 0 1 0-4 4h.25a.75.75 0 0 0 0-1.5h-.25A2.5 2.5 0 1 1 17 14v5a2.506 2.506 0 0 0 2.5 2.5h.25a.75.75 0 0 1 0 1.5h-.25a4 4 0 0 1-3.969-3.501l-.031.001h-1a5.48 5.48 0 0 1-3.773-1.5H6.5A4.5 4.5 0 0 1 2 13.5V13C2 7.477 6.477 3 12 3");
}

</style>
