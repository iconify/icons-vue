<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lum2lfbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nearby-error-outline-sharp" /></template>
<style>
.lum2lfbfy {
  fill: currentColor;
  d: path("M19.885 18v-7.5h1V18zm.493 2.654q-.264 0-.437-.175q-.172-.175-.172-.434t.175-.44t.434-.182t.44.179t.182.443t-.179.437t-.443.172m-8.993.338L2.392 12l8.993-8.992l5.73 5.692v1.83l-5.73-5.73l-7.2 7.2l7.2 7.2l5.73-5.73v1.83zm0-5.477L7.869 12l3.516-3.516L14.9 12z");
}

</style>
