<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr3if_uah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-phone-outline-sharp" /></template>
<style>
.jr3if_uah {
  fill: currentColor;
  d: path("M6 22v-7h1v3.5h10v-13H7V9H6V2h12v20zm1-2.5V21h10v-1.5zm3-4.192l-.708-.708l2.089-2.1H2.5v-1h8.88L9.293 9.4L10 8.692L13.308 12zM7 4.5h10V3H7zm0 0V3zm0 15V21z");
}

</style>
