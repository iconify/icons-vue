<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jycup_u1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:raven-sharp" /></template>
<style>
.jycup_u1j {
  fill: currentColor;
  d: path("M9.808 17.23L8.235 21l-.927-.385l1.469-3.524q-2.535-.47-4.156-2.437T3 10.116V6.327q0-1.38.973-2.354Q4.946 3 6.327 3q.377 0 .733.091q.356.092.702.234l4.892 2.04l-3 1.154v1.943l7.33 4.923h-7.08q-1.113 0-1.884-.77t-.77-1.884h-1q0 1.515 1.07 2.585q1.069 1.068 2.584 1.068H18.5l1.942 1.328L21.02 19h-1.25l-.75-1.77h-5.615V21h-1v-3.77zM5.807 5.808q-.21.21-.21.52t.21.52t.52.21t.52-.21t.21-.52t-.21-.52t-.52-.21t-.52.21");
}

</style>
