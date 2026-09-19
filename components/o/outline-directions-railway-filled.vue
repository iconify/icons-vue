<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm2q81-vb"/><circle class="ebl1rtbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-directions-railway-filled" /></template>
<style>
.cm2q81-vb {
  fill: currentColor;
  d: path("M12 2c-4 0-8 .5-8 4v9.5C4 17.43 5.57 19 7.5 19L6 20v1h12v-1l-1.5-1c1.93 0 3.5-1.57 3.5-3.5V6c0-3.5-3.58-4-8-4m0 2c3.71 0 5.13.46 5.67 1H6.43c.6-.52 2.05-1 5.57-1m6 11.5c0 .83-.67 1.5-1.5 1.5h-9c-.83 0-1.5-.67-1.5-1.5V12h12zm0-5.5H6V7h12z");
}

.ebl1rtbwa {
  cx: 12px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
