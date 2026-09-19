<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iud3xt7yz"/><path class="a_0xr7bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-domain-verification" /></template>
<style>
.a_0xr7bkz {
  fill: currentColor;
  d: path("M3 4v16h18V4zm16 14H5V8h14z");
}

.iud3xt7yz {
  fill: currentColor;
  d: path("m16.6 10.88l-1.42-1.42l-4.24 4.25l-2.12-2.13L7.4 13l3.54 3.54z");
}

</style>
