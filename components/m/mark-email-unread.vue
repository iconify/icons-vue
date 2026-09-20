<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-i9tvbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-email-unread" /></template>
<style>
.z-i9tvbtv {
  fill: currentColor;
  d: path("M17.23 7.539q-.73-.731-.73-1.77T17.23 4T19 3.27t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73M4.617 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h9.947q-.043.25-.053.49q-.009.24.014.51q.04.762.316 1.44q.274.677.734 1.221L12 11L4.308 6L4 6.885l8 5.23l4.314-2.819q.54.458 1.225.716q.684.257 1.461.257q.512 0 1.027-.125T21 9.77v7.616q0 .69-.462 1.152T19.385 19z");
}

</style>
