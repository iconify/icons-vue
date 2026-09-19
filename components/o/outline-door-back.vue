<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6z7jnqnv"/><path class="w_ir-7hca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-door-back" /></template>
<style>
.t6z7jnqnv {
  fill: currentColor;
  d: path("M19 19V5c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v14H3v2h18v-2zm-2 0H7V5h10z");
}

.w_ir-7hca {
  fill: currentColor;
  d: path("M9 11h2v2H9z");
}

</style>
