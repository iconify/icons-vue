<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msazxebjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-minus-1-outline-rounded" /></template>
<style>
.msazxebjk {
  fill: currentColor;
  d: path("M11.702 14.32q-.136-.053-.267-.184L7.046 9.749q-.14-.14-.153-.341t.153-.366q.16-.16.354-.16t.354.16L12 13.28l4.246-4.24q.14-.141.342-.153t.366.153q.16.159.16.353t-.16.354l-4.389 4.389q-.13.13-.267.183q-.136.053-.298.053t-.298-.053");
}

</style>
