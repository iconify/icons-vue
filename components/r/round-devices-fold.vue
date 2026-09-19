<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwbj83bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-devices-fold" /></template>
<style>
.pwbj83bst {
  fill: currentColor;
  d: path("M20 3h-3c0-1.43-1.47-2.4-2.79-1.84l-3 1.29C10.48 2.76 10 3.49 10 4.29V19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16h-5.33l1.12-.48c.73-.32 1.21-1.04 1.21-1.84V5h3zM2 3h2v2H2zm0 16h2v2H2zm0-4h2v2H2zm0-4h2v2H2zm0-4h2v2H2zm4-4h2v2H6zm0 16h2v2H6z");
}

</style>
