<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o75u76x7m"/><path class="u0uqtx1rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siderbar-bold-duotone" /></template>
<style>
.o75u76x7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.172 4.172C2 5.343 2 7.229 2 11v2c0 3.771 0 5.657 1.172 6.828S6.229 21 10 21h5V3h-5C6.229 3 4.343 3 3.172 4.172");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.u0uqtx1rd {
  fill: currentColor;
  d: path("M5.5 9.25a.75.75 0 0 0 0 1.5h6a.75.75 0 0 0 0-1.5zm1 4a.75.75 0 0 0 0 1.5h4a.75.75 0 0 0 0-1.5zM22 13v-2c0-3.771 0-5.657-1.172-6.828c-.974-.975-3.192-1.139-5.828-1.166v17.988c2.636-.027 4.854-.191 5.828-1.166C22 18.657 22 16.771 22 13");
}

</style>
