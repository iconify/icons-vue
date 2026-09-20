<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th_gy4bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-charge-outline-sharp" /></template>
<style>
.th_gy4bcx {
  fill: currentColor;
  d: path("m11.577 16.23l2.539-5.076h-1.693V7.769l-2.538 5.077h1.692zM6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm0 0V3z");
}

</style>
